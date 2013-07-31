PowerManagement
===============
Plugin for PhoneGap Build

This is adapted from code licensed by Wolfgang Koller. 
https://github.com/phonegap/phonegap-plugins/tree/master/iOS/PowerManagement

The original plugin was not compatible with PhoneGap Build.  We created a plugin.xml for ios.
Android will follow shortly, but we are not deploying there right now and cannot test it.

The rest of this file is edited the original readme
---------

The PowerManagement plugin offers access to the devices power-management functionality.
It should be used for applications which keep running for a long time without any user interaction.

For details on power functionality see:

* Android: [PowerManager](http://developer.android.com/reference/android/os/PowerManager.html)
* iOS: [idleTimerDisabled](http://developer.apple.com/library/ios/documentation/UIKit/Reference/UIApplication_Class/Reference/Reference.html#//apple_ref/occ/instp/UIApplication/idleTimerDisabled)
* WindowsPhone: [UserIdleDetectionMode](http://msdn.microsoft.com/en-US/library/windowsphone/develop/microsoft.phone.shell.phoneapplicationservice.useridledetectionmode%28v=vs.105%29.aspx)

Usage (PhoneGap Build)
---------
Add the following xml to your config.xml to always use the latest version of this plugin: 
`<gap:plugin name="com.simplec.plugins.powermanagement" />`


License
=======
Copyright (C) 2011-2013 Wolfgang Koller

This file is part of GOFG Sports Computer - http://www.gofg.at/.

GOFG Sports Computer is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

GOFG Sports Computer is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with GOFG Sports Computer.  If not, see <http://www.gnu.org/licenses/>.

