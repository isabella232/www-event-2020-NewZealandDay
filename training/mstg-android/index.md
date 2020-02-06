---
layout: full-width
title: OWASP NZ Day Training
displaytext: MSTG Hands-on - Android Edition
tags: nzday2020
---

![Conference Web Banner](../../assets/images/Web_Banner-OWASP_NZ_Day_2020.jpg)

# Mobile Security Testing Guide Hands-On: Android Edition

## One-Day Interactive Training - OWASP New Zealand Day 2020

## Abstract

How do I bypass SSL Pinning on a Flutter app, and what can I do with Frida when testing on a non-jailbroken device? All of this, and more, will be covered in this fast paced one-day course. Students will have lots of hands-on time to exploit vulnerabilities in apps created by the trainer.

The course is designed for beginners, but is also useful for intermediate students already familiar with testing mobile apps. Hands-on exercises are usually presented in two versions - 'skid' and 'leet' - to provide challenges for either skill level.

## Overview

This course teaches you how to analyse an Android app for security vulnerabilities, by going through the different phases of testing, including dynamic testing, static analysis and reverse engineering. The instructors will share their experiences and many small tips and tricks to attack mobile apps.

At the beginning of the course we start by giving an overview of the Android Platform and it’s Security Architecture. It is no longer mandatory for students to bring their own Android device, instead a cloud-based virtualized Android device will be provided for each student. These are some of the topics that will be covered during the course:

* Frida crash course to kick-start with dynamic instrumentation on Android apps
*  Function Hooking in a Hybrid app framework (Flutter) to reverse engineer custom Keystore implementation and bypass SSL pinning
*  Identifying and exploiting a real word deeplink vulnerability
*  Application repackaging to defeat Network Security Configuration
*  Usage of dynamic Instrumentation with Frida to:
    * break end-to-end encryption (Frida/Brida);
    * bypass Frida detection mechanisms; and
    * bypass multiple root detection mechanisms

At the end of the day, small groups will be created (2-3 students) and time will be given to investigate an app with the newly learned skills. Every team is then encouraged to make a short presentation about the analysed vulnerability.

After successful completion of this course, students will have a better understanding of how to test for vulnerabilities in Android apps, how to mitigate them and how to execute tests consistently. The course is based on the OWASP Mobile Security Testing Guide (MSTG) and is conducted by one of the author himself. The OWASP MSTG is a comprehensive and open source guide about mobile security testing for both iOS and Android.

## Target Audience 

Students who have mobile application development and application penetration testing experience enjoyed and benefited the most from the course. The following are common backgrounds we have seen in previous classes:

* Penetration Testers that want to achieve full coverage when testing a mobile app
* Developers that want to understand how attacks can be executed against their mobile apps
* Security Auditors that want to know how to work with an accepted industry standard for mobile security
* Internal Awareness Teams / Trainers to communicate the latest attacks and vulnerabilities to their students
* Infosec personnel interested in defending and attacking mobile attacks
* Anyone interested in learning more about mobile attacks

## Course Details 

**Dates:** Wednesday, 19 February 2020

**Time:** 8:45 a.m. to 5:30 p.m.

**Course Fee:** NZ $625.00 (plus EventBrite fees)

**Registration Site:** [https://owaspnz2020-training.eventbrite.com](https://owaspnz2020-training.eventbrite.com)

**Prerequisite Skills:**

* A basic understanding of mobile apps
* An interest in security and learning new things
* Basic experience with the command line

**Attendees Should Bring:** 

An Android hardware device is not needed by the participants and will also not be provided. The Android hands-on exercises of the training will instead be executed in a cloud-based virtualised environment that allows attendees to access a rooted Android device during the training. One Android instance will be provided for each participant.

The following technical prerequisites need to be fulfilled by participants in order to be able to execute and follow all exercises:

* Laptop (Windows or MacBook) with at least 8 GB Ram, 25 GB of free disk space, working Wi-Fi
* Full administrative access, in case of any issues with the environment
* VirtualBox installed

**Attendees Will Be Provided:**

* All presentation slides, in PDF format
* Access to a private GitHub repository, containing:
    * All tools and scripts used during the class
    * Android apps used for the hands-on exercises

**Instructor:** Sven Schleier

**Instructor's Organisation:** Seven Consulting

== Course Objectives ==

Key take-aways for attendees include:

* Android security fundamentals to understand the security mechanisms that are in place by the OS
* Preparing a penetration testing environment for Android and clarifying the limitations and benefits of each (real device, emulator, rooted etc.)
* Hands-on exercises that are based on Android Apps that are build specifically for each test case to gain an understanding of different vulnerabilities
* Demonstrate implementation of the latest security best practices to mitigate vulnerabilities in mobile apps or reduce the attack surface
* Basic introduction into dynamic instrumentation by using Frida and different frameworks on top of Frida (e.g. House)
* Basic Reverse Engineering of Android Apps to bypass client-side security controls, such as disabling Root Detection or SSL Pinning

== Course Outline ==

* Overview of Android Platform and Security Mechanisms
  * Android Security Architecture (Bootloader, Permission model, Sandboxing etc.)
  * App Communication with the Operating System (IPC, Intent etc.)
  * Runtime Environment (Dalvik vs. ART)

* Hands-on: Creating an Android Testing Environment
  * Android Debug Bridge (ADB)
  * Setting up an Android Genymotion EC2 instance in the cloud for testing (execution of script by trainers before the class starts, which will provision a Genymotion VM in AWS for each student)
  * Differences and limitations between testing in an emulator/simulator and a physical device

* Hands-on: Dynamic Analysis
  * Analysing HTTP traffic by using Burp Suite
  * Analysing apps build on frameworks that are not using the system Proxy; Students will be intercepting an app build with Flutter
  * Analysing all outgoing (non-HTTP) traffic on the Android device, by chaining tcpdump, netcat, adb and Wireshark together
  * Piping network traffic from an Android device to your laptop through USB by using adb reverse, e.g. in case of client isolation in the Wifi network

* Hands-on: Dynamic Instrumentation 101
  * Introduction into Frida and tool landscape (usage of House)
  * Identify and hook functions of an Android App
  * Using Frida Server on a rooted device
  * Using Frida Gadget through repackaging of an app with objection to test on non-rooted devices

* Hands-on: Bypassing SSL Pinning
  * Explanation of SSL Pinning functionality and implementations
  * By using Xposed (rooted device)
  * By using Objection (non-rooted device)
  * Lab to show different ways of bypassing SSL Pinning, including when implemented with Network Security Configuration by using “Magisk Trust User Certs”

* Hands-on: Android Application Structure
  * Decompiling APK
  * APK file structure
  * Understanding and Analysing AndroidManifest.xml
  * Lab to show repackaging and analysing an app with Network Security Configuration

* Hands-on: Static Analysis
  * Identifying a Deeplink vulnerability in a Kotlin App
  * Automated Static Analysis with MobSF; showing quick wins and it’s limitations
  * Lab to exploit the vulnerability

* Hands-on: Testing for Sensitive Data in Local Storage (Shared Preferences, SQLite Databases, Internal and External Storage) and secure usage of KeyStore

* Hands-on: Android Reverse Engineering
  * Using Dynamic Instrumentation to bypass multiple root detection functions and compare it to patching Smali and using Xposed (Pros/Cons)
  * Breaking End-to-End Encryption by using Frida/Brida
  * Bypass detection mechanisms for Dynamic Instrumentation (Frida)

* Team exercise: Create small groups (2-3 students) to investigate an app with the newly learned skills. Every team is then encouraged to make a short presentation about the analysed vulnerability.

## Your Instructor

**Sven Schleier** - Sven made several stops at big consultant companies and small boutique firms in Germany and Singapore and became specialised in Application Security and has supported and guided software development projects for Mobile and Web Applications during the whole SDLC. Besides his day job Sven is one of the core project leaders and authors of the OWASP Mobile Security Testing Guide and OWASP Mobile Application Security Verification Standard and has created the OWASP Mobile Hacking Playground. Sven is giving talks and workshops about Mobile and Web Application Security worldwide to different audiences, ranging from developers to students and penetration testers.
