if(CMAKE_SYSTEM_NAME MATCHES "Windows")
	add_executable(FileSearch "main.cpp")
endif()

if(CMAKE_SYSTEM_NAME MATCHES "Linux")
	add_executable(file_search "main.cpp")
endif()

if(CMAKE_SYSTEM_NAME MATCHES "FreeBSD")
	add_executable(file_search "main.cpp")
endif()
