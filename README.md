MobileControlRTC
================

Layout
----

![MobileControlRTC](https://farm8.staticflickr.com/7502/15477956049_bcb4ec183f_o.png)

Features
----
  * When the target velocity input it will just output velocity
  * When the target pose input it will control Kobuki moves to the postion
  * The flag will be true if Kobuki arrives the target position

Requirements
----
  * OS
   * Linux Distributions
   * Windows
  * Softwares
   * OpenRTM-aist C++ 1.1 or later
   * CMake 2.8

Port
----

| Name     | Type          | Data Type   | Purpose |
| -------- | ------------- | ----------- | ------- |
| target_velocity   | In       | RTC::TimedVelocity2D | The target velocity for the robot |
| target_pose  | Out      | RTC::TimedPose2D  | The target pose for the robot |
| current_pose     | In      | RTC::TimedPose2D   | The target pose for the robot|
| target_velocity | Out | RTC::TimedVelocity2D | The current pose of the robot |
| flag | Out | RTC::TimedBoolean | The arrival flag if the robot arrived the target pose |

License
----

Licensed under the [Apache License, Version 2.0][Apache]  
Distributed under the [MIT License][mit].  
Dual licensed under the [MIT license][MIT] and [Apache License, Version 2.0][Apache].  
 
[Apache]: http://www.apache.org/licenses/LICENSE-2.0
[MIT]: http://www.opensource.org/licenses/mit-license.php
