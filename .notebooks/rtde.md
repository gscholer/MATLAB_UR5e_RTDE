`movej`: move to a position in joint-space (linear interpolation) 
https://github.com/gscholer/MATLAB_UR5e_RTDE/blob/c09ecbf85a06304bd64145009e730208e881e6f4/rtde/rtde.m#L96-L98

the second parameter `jointOrPose` can be `"joint"` or `"pose"`:
https://github.com/gscholer/MATLAB_UR5e_RTDE/blob/c09ecbf85a06304bd64145009e730208e881e6f4/rtde/rtde.m#L104-L107

`jointOrPose`'s default value is `"pose"`:
https://github.com/gscholer/MATLAB_UR5e_RTDE/blob/c09ecbf85a06304bd64145009e730208e881e6f4/rtde/rtde.m#L117-L119

the unit of first three values of `target` parameter are `mm`:
https://github.com/gscholer/MATLAB_UR5e_RTDE/blob/c09ecbf85a06304bd64145009e730208e881e6f4/rtde/rtde.m#L149-L153

https://github.com/gscholer/MATLAB_UR5e_RTDE/blob/c09ecbf85a06304bd64145009e730208e881e6f4/examples/example_8_letters.m#L46-L50
