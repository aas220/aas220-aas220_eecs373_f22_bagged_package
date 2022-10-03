# aas220-aas220_eecs373_f22_bagged_package

**TO START ORGINAL**
Pull navvis_description package from https://github.com/aas220/eces373_f22_aas220_navvis_description (Will probably need anyways as this package depends on it)
Catkin_make
Source devel/setup.bash
from src folder outside of package run roslaunch navvis_description/launch/display.launch

**TO START THE ONE WITH THE NEW JOINTS**
Pull this package
Catkin_make
source devel/setup.bash
from src folder outside of package run roslaunch bagged_package/launch/display.launch

Make sure that you have the glennan_maps package you linked us

**TO START WITH MAP**
from src folder outside of package(after following above steps)
run roslaunch bagged_package/launch/display_with_map.launch
