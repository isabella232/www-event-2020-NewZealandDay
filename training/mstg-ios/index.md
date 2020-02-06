---
layout: full-width
title: OWASP NZ Day Training
displaytext: MSTG Hands-on - iOS Edition
tags: nzday2020
---

[![Conference Web Banner](../../assets/images/Web_Banner-OWASP_NZ_Day_2020.jpg)](/www-event-2020-NewZealandDay)

[Back to Conference Home Page](/www-event-2020-NewZealandDay)
{: style="text-align: right; font-size: small;" }

# Mobile Security Testing Guide Hands-On: iOS Edition

## One-Day Interactive Training - OWASP New Zealand Day 2020

## Abstract

How do I bypass SSL Pinning on a Flutter app, and what can I do with Frida when testing on a non-jailbroken device? All of this, and more, will be covered in this fast paced one-day course. Students will have lots of hands-on time to exploit vulnerabilities in apps created by the trainer.

The course is designed for beginners, but is also useful for intermediate students already familiar with testing mobile apps. Hands-on exercises are usually presented in two versions - 'skid' and 'leet' - to provide challenges for either skill level.

## Overview

This course teaches you how to analyse an iOS app for security vulnerabilities, by going through the different phases of testing, including dynamic testing, static analysis and reverse engineering. The instructor will share his experiences and many small tips and tricks to attack mobile apps.

At the beginning of the course we start by giving an overview of the iOS Platform and its Security Architecture (Hardware Security, Code Signing, Sandbox, Secure Boot, Security Enclave, etc.). After explaining what an IPA container is and the iOS file system structure we start creating an iOS testing environment and make a deep dive into various topics and techniques, including:

* Analyzing iOS applications that use non-HTTP traffic
* Frida crash course to kick-start with dynamic instrumentation for iOS apps 
* Bypassing SSL Pinning with SSL Kill Switch and Objection 
* Evaluating different implementations of Touch ID / Face ID and ways to bypass them 
* Testing methodology without a jailbroken device by repackaging an IPA with the Frida Gadget 
* Testing stateless authentication mechanisms such as JWT in an iOS Application 
* Using Frida for Runtime Instrumentation of iOS Apps to bypass:
  * Anti-Jailbreaking mechanisms; 
  * Frida detection mechanism; and 
  * Other client side security controls

At the end of the day, small groups will be created (2-3 students) and time will be given to investigate an app with the newly learned skills. Every team is then encouraged to make a short presentation about the analysed vulnerability.

After successful completion of this course, students will have a better understanding of how to test for vulnerabilities in iOS apps, how to mitigate them and how to execute tests consistently. The course is based on the OWASP Mobile Security Testing Guide (MSTG) and the OWASP Mobile AppSec Verification Standard (MASVS) and is conducted by one of the authors himself. The OWASP MSTG is a comprehensive and open source guide about mobile security testing for both iOS and Android.

## Target Audience 

Students who have mobile application development and application penetration testing experience enjoyed and benefited the most from the course. The following are common backgrounds we have seen in previous classes:

* Penetration Testers that want to achieve full coverage when testing a mobile app
* Developers that want to understand how attacks can be executed against their mobile apps
* Security Auditors that want to know how to work with an accepted industry standard for mobile security
* Internal Awareness Teams / Trainers to communicate the latest attacks and vulnerabilities to their students
* Infosec personnel interested in defending and attacking mobile attacks
* Anyone interested in learning more about mobile attacks

## Course Details 

**Dates:** Thursday, 20 February 2020

**Time:** 8:45 a.m. to 5:30 p.m.

**Course Fee:** NZ $625.00 (plus EventBrite fees)

**Registration Site:** https://owaspnz2020-training.eventbrite.com

**Prerequisite Skills:**

* A basic understanding of mobile apps
* An interest in security and learning new things
* Basic experience with the command line

**Attendees Should Bring:** 

**You need to bring your own iOS device, with at least iOS 11, to complete all exercises.**

The following technical prerequisites need to be fulfilled by participants in order to be able to execute and follow all exercises:

* MacBook with at least 8 GB Ram, 25 GB of free disk space, working Wi-Fi
* Full administrative access, in case of any issues with the environment
* VirtualBox installed

**Attendees Will Be Provided:**

* All presentation slides, in PDF format
* Access to a private GitHub repository, containing:
** All tools and scripts used during the class
** Android apps used for the hands-on exercises

**Instructor:** Sven Schleier, Seven Consulting

## Course Objectives

Key take-aways for attendees include:

* iOS security fundamentals to understand the security mechanisms that are in place by the OS
* Preparing a penetration testing environment for iOS and clarifying the limitations and benefits of each (real device, emulator, jailbroken etc.)
* Hands-on exercises that are based on iOS Apps that are build specifically for each test case to gain an understanding of different vulnerabilities
* Demonstrate implementation of the latest security best practices to mitigate vulnerabilities in mobile apps or reduce the attack surface
* Basic introduction into dynamic instrumentation by using Frida and different frameworks on top of Frida (e.g. Passionfruit)
* Basic Reverse Engineering of iOS Apps to bypass client-side security controls, such as disabling Jailbreak Detection or SSL Pinning

## Course Outline

* Overview of iOS Platform and Security Mechanisms
  * iOS Security Architecture (Hardware Security, Code Signing, Sandbox, Secure Boot, Security Enclave)
  * Explaining IPA Container and Structure on the iOS File System

* Creating an iOS Testing Environment
  * Testing with and without Jailbreak and it’s limitations
  * Testing in an emulator compared to a real device
  * Setting up the iOS device
  * Describing various ways of installing iOS Apps

* Demonstration of testing iOS Apps without Jailbreak:
  * Repackaging an IPA with the Frida Gadget by using Objection
  * Overview of Objection and its limitations

* Hands-on: Static Analysis
  * Decrypting an app with Fairplay Encryption by using clutch or frida-ios-dump
  * Using class-dump
  * Automated Static Analysis with MobSF
  * App Transport Security (ATS)

* Hands-on: Dynamic Instrumentation 101 - iOS
  * Introduction into Frida and it’s basics (hooking, overloading, usage of Frida CLI and Frida scripts etc.)
  * Identify and hook functions of an iOS App
  * Using Frida for testing iOS Apps
  * Using Frida Server on a jailbroken device
  * Repackaging of an app with Frida Gadget to test on non-jailbroken devices

* Hands-on: Dynamic Analysis
  * Analysing HTTP traffic through Burp Suite
  * Piping network traffic from an iOS device to the laptop via USB by using usbmuxd, e.g. in case of client isolation in the Wifi network
  * Analysing apps build on frameworks that are not using the system Proxy (Xamarin)
  * Analysing all non-HTTP traffic through a remote virtual interface on macOS

* Hands-on: Bypassing SSL Pinning
  * Identifying usage of SSL Pinning
  * Lab to show different ways of bypassing SSL Pinning, by using SSL Kill Switch (jailbroken device) and by using Objection (non-jailbroken device)

* Hands-on: Testing for Touch ID /Face ID Bypass
  * Explanation of Touch ID / Face ID functionality and implementations
  * Bypassing Biometric authentication through Needle and Objection

* Hands-on: Testing for Sensitive Data in Local Storage
  * Explanation of different ways to store data on iOS (Core Data, plist, Sqlite…) and how to store it securely by using the Keychain
  * Analyse local storage by using Objection, Passionfruit and Xcode

* Hands-on: Testing Stateless Authentication with JSON Web Token (JWT) in an iOS App
  * Dynamic Testing by using Burp Suite
  * Analyse storage for access tokens
  * Apply known attacks against JWT

* Hands-on: Reverse Engineering
  * Basic Reverse Engineering of an iOS app
  * Bypassing Client-Side Security controls through dynamic instrumentation with Frida
    * Anti-Jailbreaking Mechanisms
    * Tampering detection of Frida

* Team exercise: Create small groups (2-3 students) to investigate an app with the newly learned skills. Every team is then encouraged to make a short presentation about the analysed vulnerability.

## Your Instructor

**Sven Schleier** - Sven made several stops at big consultant companies and small boutique firms in Germany and Singapore and became specialised in Application Security and has supported and guided software development projects for Mobile and Web Applications during the whole SDLC. Besides his day job Sven is one of the core project leaders and authors of the OWASP Mobile Security Testing Guide and OWASP Mobile Application Security Verification Standard and has created the OWASP Mobile Hacking Playground. Sven is giving talks and workshops about Mobile and Web Application Security worldwide to different audiences, ranging from developers to students and penetration testers.
