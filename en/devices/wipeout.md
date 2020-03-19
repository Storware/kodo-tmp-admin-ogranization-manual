# Mobile device erase

## Overview

{% hint style="info" %}
**Remote device erase is supported only for Android devices**
{% endhint %}

Wipeout function allows to erase data stored on Android device. Simply send wipeout request to device and KODO will do the rest. 

KODO will send push notification to selected device with wipeout request, device must have network access to receive it.

{% hint style="warning" %}
KODO wipeout feature erase only data \(contacts, calendars, galleries, files\) that were protected by KODO \(configured via policy\) 
{% endhint %}

{% hint style="info" %}
KODO-EMM is a MDM system that will allow you to fully control and erase Android and iOS devices. Read more at [https://storware.eu/en/storware-kodo-emm/](https://storware.eu/en/storware-kodo-emm/)
{% endhint %}

## Performing erase \(wipeout\)

To erase device:

1. **Go to the list of devices. Select** `DEVICES` **from main menu**
2. **Click on device name you want to erase**
3. **Click the `...` button, select** `WIPEOUT` **and confirm your action with** `OK` ****

{% hint style="info" %}
You can also use Quick Action menu "Wipeout" item from Devices list
{% endhint %}

## Status of performed erase actions

To view a list of wipeouts, and their statues, performed on devices, select `Wipeout` from the main menu.

Policies list table view consist of following columns:

| Field | Description |
| :--- | :--- |
| Device | Name of device  |
| User | Owner of device |
| Platform | Device OS |
| Device ID | Device internal ID number |
| Start date | Date when erase push was send |
| Start by | Name of administrator that started process  |
| Status | Status of erase process  |



