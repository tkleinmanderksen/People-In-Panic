#People-In-Panic

## Introduction
My father is daignosed with a muscle disease [ALS](https://en.wikipedia.org/wiki/Amyotrophic_lateral_sclerosis)  what for now is that he cannot raise his arms or hands corretly to use the phone when he want to reach my mother in the case he needs her. In the search for a device that my father can use when my mother is away to a neighbor or getting groceries there are only home-security alarms with a subscription or with a device what is locker to the house. In the case that my father is over by my place he also need to call me or my mother in case of need/panic. 

I discovered a small "key-finder" device [iTag](https://github.com/s4ysolutions/itag) that has a button and can be used with his mobile phone (Android 10). So there are only purchase cost of € 1.89 and his mobilephone with a telephone subscription.

## Short-Objective
* iTag
  * Connect iTag (fixed HW-address) to Application
  * Subscribe to button press event
  * Raise event when iTag is disconnected
* Logic
  * When button pressed, dad is in need (Emergency):
    * Call mom and set phone on speakermode
    * SMS mom with message that the call is initated with mobileapplication 
  * Test "Emergency mode"

## Long-term Objectives
* iTag
  * Connect a iTag with a search action.
  * Monitor battery iTag and raise event under 25%
* Logic
  * Set a custom phonenumer for Emergency mode, maybe selected by a contactpicker.

## Resources
* Visual Studio 2019 Community Edition
* Xamarin
* Xamararin.Bluetooth.BLE
