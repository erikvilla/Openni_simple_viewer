# Openni_simple_viewer
Simple viewer using openni 2

## Eclipse configuration

### Linking libraries
In order to run the project you need to point `DYLD_LIBRARY_PATH` environment variable to `<path_to>/OpenNI2/Bin/x64-Release/` in Eclipse's run configurations. To get there, just secondary click in the project, click `Run Configurations`, click `Java application` on the side menu, select environment tab and add `DYLD_LIBRARY_PATH`.
Note: If you ran the project already a default run configuration will exist when you get to this point.

### Openni dependency
Openni is a required dependency for this project to be built, in your Java build path add `org.openni.jar` library.

### Native libraries
In order to point openni library to the native ones, right click `org.openni.jar` in `Referenced libraries`, click properties, go to Native Library and point to `lib` folder of the project where jni and dylib are located.
