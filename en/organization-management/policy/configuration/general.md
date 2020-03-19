---
description: The GENERAL tab contains a basic policy configuration.
---

# General settings

![General policy settings](../../../../.gitbook/assets/policies_general_s%20%281%29.png)

## BASIC SETTINGS

**Set as default policy**  
Set policy as a default for newly synchronized users 

**Allow user to modify policy**  
User can add new objects to protect - modification will only concern a user device where the modification has been made, server settings will be not changed

## **PRIVACY SETTINGS** 

**Allow admin to restore user files**  
Allow administrator to restore user files directly to his workstation.

## **PASSWORD SETTINGS**

Password requirements for local users accounts:

* **Minimal password length**
* **Require uppercase letters**
* **Require lowercase letters**
* **Require numbers**
* **Require special characters**

## **MOBILE SETTINGS**

**Allow backups only over WiFi**  
Mobile device backup will be allowed only over WiFi network.

**Require PIN authentication**  
Always require PIN code when logging in to the application instead of password

**Maximum session time**  
Max. time which the KODO application can be run at background without user re-authentication.

**Retention period for file versions and Maximum number of file versions**

## **MYKODO SETTNGS**

**myKODO enabled**  
Enable or disable myKODO on devices

**Windows location of myKODO folder**  
Path to folder that will store myKODO data on Windows

**macOS location of myKODO folder**  
Path to folder that will store myKODO data on macOS

**File link expiration**  
The maximum lifetime for a link generated by user

**Require password for file links**  
Require that every link generated by user must be protected by password

**Allow sharing folders**  
Allow to share myKODO folders with other KODO users

**Allow sharing files via filelink**  
Allow myKODO files sharing via web links

## **RISK NOTIFICATION SETTINGS**

**Send email notification for unprotected desktops**  
If desktop device will change status to unprotect, device owner will be notified by e-mail

**Show as desktop "Unprotected" after**  
Number of days, without any contact from desktop device, after which status will be changed to unprotected

**Send email notification for unprotected mobiles**  
If mobile device will change status to unprotect, device owner will be notified by e-mail

**Show as mobile "Unprotected" after**  
Number of days, without any contact from mobile device, after which status will be changed to unprotected

## ENCRYPTION SETTINGS

**Allow users to encrypt their data using their own encryption key**  
Allow user to turn on client-side data encryption. Data are encrypted using key based on password provided by user. Encrypted data can't be restored by administrator.

**Enable server-side encryption for myKODO files**   
Encrypt myKODO files on server-side. Key is generated and stored on server.
