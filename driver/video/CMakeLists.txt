#################################################################################
### $Id: CMakeLists.txt 6458 2010-05-31 11:38:51Z FloSoft $
#################################################################################

ADD_SUBDIRECTORY( WinAPI )
IF(BUILD_GLFW_DRIVER)
       ADD_SUBDIRECTORY( GLFW )
ENDIF(BUILD_GLFW_DRIVER)
IF(BUILD_SDL_DRIVER)
       ADD_SUBDIRECTORY( SDL )
ENDIF(BUILD_SDL_DRIVER)

#################################################################################
