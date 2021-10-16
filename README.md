# ![](https://raw.githubusercontent.com/hoobs-org/HOOBS/master/docs/logo.png)
Provides the API interface between HOOBS and SmartThings

HOOBS Plugin for SmartThings

## Installation

* Log into your SmartThings account at [SmartThings IDE](https://account.smartthings.com/login)

* Click on **My Locations** and select your hub.

* Click on **My SmartApps**

* Copy [Groovy Code](https://raw.githubusercontent.com/hoobs-org/smartthings/main/app.groovy)

* Click on **New SmartApp**

* Click on the **From Code** tab. Paste the code in the area provided.

* Click **Create** in the bottom left corner of the page.

* Go to **App Settings** in the top right corner

* Go to **OAuth**. Click on **Enable OAuth in Smart App** and Click on **Update**

* Click **Save**, then click **Publish (For Me)**, and you should receive a confirmation that the code has been published successfully.

## Configuration

* In the [SmartThings Mobile App](https://apps.apple.com/us/app/smartthings/id1222822904), tap on **Automations**.

* Tap on the **+** then **Add SmartApp**.

* Tap on **HOOBS (Connect)**

* Configure Devices

  In **Define Device Types** there are 8 inputs that can be used to force a device to be discovered as a specific type in HomeKit.
  > Do not select the same device in more that one input. If you select a device here, do not select that same device in the other device inputs on the previous page.

  For any other devices you would like to add that weren't added in the previous step, just tap on the input next to an appropriate device group and then select each device you would like to use. (The same devices can be selected in any of the Sensor, Switch, Other inputs)

* There are several categories here because of the way SmartThings assigns capabilities. You might not see your device in one, but might in another.

* Almost all devices contain the Refresh capability and are under the "Other Devices" group.

* Some sensors don't have a refresh and are under the "Sensor Devices" group.

* Some devices, mainly Virtual Switches, only have the Switch Capability and are in the "Switch Devices" group.

  > If you select the same device in multiple categories, it will only be shown once in HomeKit. You can safely check them all in all groups, aside from the NOTICE above.**

* Tap **Next**

* Tap **Done**

* Within the App, tap on **Automation**.

* Tap on **HOOBS (Connect)**

* Tap on **Render the platform data for HOOBS** to get your **App Url** **App ID** **App Token** information.

* Add the information in the SmartThings section on the HOOBS Config screen.

## Credits
Copyright© tonesto7. All rights reserved.
