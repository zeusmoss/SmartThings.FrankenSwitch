# FrankenSwitch Device Type for SmartThings
===========

Copyright (c) 2014 [Brandon Gordon](https://github.com/notoriousbdg)

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except
in compliance with the License. You may obtain a copy of the License at:

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed
on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License
for the specific language governing permissions and limitations under the License.

##Overview

The FrankenSwitch Device Type allows for easier integration between devices that expect contact, presence, or motion sensors when the only input available is a switch.  There is a toggle on the device screen that can be used to change the behaviour of the sensors between normal, reversed, and disabled.  The first use case is with Tasker integration on Android to allow commands to be sent to a switch but SmartApps can subscribe to the status of contact, presence, or motion sensors.  The second is with Harmony Remote integration that will allow a switch to be changed while simultaneously changing the status of contact, presence, or motion sensors.

##Install Procedure

1. Create a new Device Type at https://graph.api.smartthings.com/ide/devices using the SmartApps at https://github.com/notoriousbdg/SmartThings.FrankenSwitch.
2. Create a new device at https://graph.api.smartthings.com/device/list using the Device Type created in step 1.

##Revision History

2014-10-14  v0.0.0  Forked from http://thinkmakelab.com/2014/06/11/how-to-create-a-virtual-switch-in-smartthings/
2014-10-13  v0.0.1  Initial release

The latest version of this file can be found at:
  https://github.com/notoriousbdg/SmartThings.FrankenSwitch
