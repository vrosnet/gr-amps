########################################################################
# Setup dependencies
########################################################################
find_package(Doxygen)

########################################################################
# Begin conditional configuration
########################################################################
if(ENABLE_DOXYGEN)

########################################################################
# Add subdirectories
########################################################################
add_subdirectory(doxygen)

endif(ENABLE_DOXYGEN)
