# Cylaris AwesomeAutomation

Cylaris AWESOMEAUTOMATION is an **awesome** repository of automation scripts to make things easier in your life without sacrificing your privacy and security.

This repo is for:
- Linux Nerds
- Tinfoil Hats
- Anyone who cares about privacy and security

### Content

- Tasker Scripts

Tasker is an automation app for Android. It is by far the most powerful mobile automation tool, developed by @joaomgcd. We use it to automate all the things.

- PHP Scripts

We have a website hosting a few PHP scripts that are being frequently updated, again, they don't collect your data and are totally free to use. They're also pretty rapid: [tools.cylaris.org](https://tools.cylaris.org "tools.cylaris.org")

Please excuse the format for now, I'll sort it, I promise.

- Mobile Apps (.apk)

Mobile Apps that do things that other mobile apps don't. These are way too cool for the app store. 

# automation - useful and private
<img width="300px" border=0 src="https://cylaris.org/assets/cylarisghp.svg"></img>

![](https://img.shields.io/github/commit-activity/m/cylaris/awesomekql?color=purple&style=flat-square) ![](https://img.shields.io/website?down_color=red&style=flat-square&up_color=purple&url=https%3A%2F%2Fcylaris.org) ![](https://img.shields.io/keybase/pgp/cylaris?color=purple&style=flat-square) ![](https://img.shields.io/github/license/cylaris/awesomekql?color=purple&style=flat-square)


# Content

## Tasker - SMS Profiles

SMS Profiles on Tasker are a great way to include automation in your daily life without the need to install unknown app from unknown developer to monitor your location 24/7, not only is that not private, but it will drain your battery. Things like your welfare and that of your family is private, such that a private company should not be collecting data around it. Good news - you can do it yourself with these templates.

**Reply Location to Chosen Contact(s) on Keyword**
- [Reply Location on Keyword/Contact](https://github.com/cylaris/awesomeautomation/blob/main/SMS/ReplyLocationContact.XML "SMS - Reply Location on Keyword/Contact")

This profile will allow your phone to fetch location and reply to your chosen sender, who has sent your chosen keyword, with your realtime location. This will be in the form of a Google Maps URL. The benefit here is that a seperate app is not required.

**Family Emergency Alert on Keyword**
- [Family Emergency Alert](https://github.com/cylaris/awesomeautomation/blob/main/SMS/FamilyEmergencyAlert.XML "Family Emergency Alert")

This profile will reference your contact tags, in this case 'FAMILY' CG:FAMILY in the profile, if a message received from them in the body contains e.g. URGENT (you specify) will cause your phone to disable any kind of do not disturb mode it was in if you are sleeping/ at work and cause a very loud beeping tone. It should be reserved for your family/friends if they urgently need to contact you or, however else you see fit.

## Tasker - Security Policy

Tasker is a nice way to add security policy to your personal device. All of us in the industry know that all primary devices, such as mobile phones, laptops, have had heavy focus on security in the last 5 years, mobile phones will continue to get this attention, as it is where we all do our business, your bank, your social life, it's all there.

Sadly, there are still many problems. Take a Linux host for instance, which do you think is more private, a Linux instance or your Android/iOS device? Spoiler: It's not your phone. 

**Admin Lock Device on Flip**
- [Admin Lock Device](https://github.com/cylaris/awesomeautomation/blob/main/SecurityPolicy/AdminLock-OnFlip.XML "Admin Lock Device")

This profile will lock your device as an Admin when device is flipped face down. You could be in a situation where anyone could force you to use FaceID/Fingerprint, but they have no way to force you to input your pin. Admin lock requires pin to unlock device.

Further, most vulnerabilities that can bypass screen lock require the phone to be in 'semi-unlocked' state, meaning FaceID/Fingerprint is usable, in this fully locked state, those are not possible.

## Contributors
- [Cam](https://sorry.wtf "Cam") :man_mechanic:	
- [Kaya](https://kaya.baby "Kaya") :martial_arts_uniform:	
