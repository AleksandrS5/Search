cmake_minimum_required(VERSION 3.16.3)

SET(Project_name Program_0) 

PROJECT(${Project_name} VERSION 1.0 LANGUAGES CXX)
SET(CMAKE_CXX_STANDARD 17) 
SET(CMAKE_CXX_STANDARD_REQUIRED True)
SET(CMAKE_CXX_FLAGS "-Wall")

 
###################   ***DO NOT EDIT***  #####################

#############  Common Instructions for all Users  ############
if(MSVC)
    SET(CMAKE_CXX_FLAGS_RELEASE "${CMAKE_CXX_FLAGS_RELEASE} /MT")
endif()

#find_package( OpenCV REQUIRED )
   
 
SET(   SOURCE 
    main.cpp   
    )
    
SET(   HEADER       
    ) 
 
ADD_EXECUTABLE(${Project_name} ${SOURCE} ${HEADER})  
# TARGET_LINK_LIBRARIES(Modem_DVB_S2 ${DIR_LIBR}/liblua53.a )  
 
