project(DataManager)

set(DataManager_SOURCES
	DataManager.h
	DataManagerImpl.h
	DataManagerImpl.cpp
    DataManagerFactory.h
    DataManagerFactory.cpp
    DataManagerFactoryImpl.h
    DataManagerFactoryImpl.cpp
)

add_library(DataManager STATIC ${DataManager_SOURCES})