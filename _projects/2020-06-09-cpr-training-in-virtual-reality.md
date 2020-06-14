---
layout: post
author: Mohan Zalake
title: CPR Training in Virtual Reality
date: 2020-06-09T00:55:37.553Z
thumbnail: /assets/img/posts/vrtraining.jpg
category: Virtual Reality
summary: VR based trainer to perform CPR. Built in a day. Hackathon Winner -
  Best First-Time Hack.
---


- - -

layout: post author: Mohan Zalake
title: CPR Training in Virtual Reality
date: 2020-06-09T00:38:51.270Z
thumbnail: /assets/img/posts/vrtraining.jpg
category: jekyll
summary: VR based trainer to perform CPR. Built in a day. Hackathon Winner -
  Best First-Time Hack.

- - -

## Inspiration

Cardiac arrest – an electrical malfunction in the heart that causes an irregular heartbeat (arrhythmia) and disrupts the flow of blood to the brain, lungs and other organs – is a leading cause of death. Each year, more than 350,000 out-of-hospital cardiac arrests occur in the United States.When a person has a cardiac arrest survival depends on immediately getting CPR from someone nearby.Almost 90 percent of people who suffer out-of-hospital cardiac arrests die.CPR especially if performed in a right way, can double or triple a person’s chance of survival. There is a strong need of making people aware and trained to perform CPR. Most of the deaths occur due to having less information about CPR or by people performing it in a wrong way or slow way.

## What it does

CPR.VR is an application which first teaches user how to perform CPR and what are the critical measures one should take while performing CPR. This application also depicts the actual hand compression gesture one should perform while giving CPR.The application also gives you feedback on the CPR therapy given by you to virtual patients by counting the right gestures of compression made by you which is required in the real CPR therapy at the appropriate rate.

## How we built it

The application is developed and designed using C# in unity engine and works on Oculus-Rift VR Headset with leap motion sensor to track hand movements.We have used leap motion hand tracking to track the hand and its position and the right gesture and counted the number of valid gestures made by the user in an appropriate time at an appropriate position and returned the feedback accordingly We have developed this application following all the rules of Human computer Interaction and used Shneiderman's "Eight Golden Rules to design the interface for the application.

## Challenges we ran into

We were new to hand gesture recognition technology. First challenge we faced was to choose which hand gesture technology to use. Then to figure out the different hand gestures recognition hardware's API and how to integrate them with Unity. We also faced difficulty in tracking hand gesture with right calibration on our Game Object. We first tried the Myo armband and was unable to perform the compression gesture with right calibration on unity.Then we switched to leap Motion and made its setup from the scratch. Learned about its API function calls. We started our project on GearVR because of switching the hand gesture recognition device.We were forced to switch the VR device too as Leap motion was not working with GearVR.

## Accomplishments that we're proud of

1st Hackathon experience for 3 of our Teammates.Learning New Technologies-Leap Motion and successfully implementing the application on Oculus-Rift VR. Fixing all the bugs and making application work as planned.

## What we learned

Unity Development using Leap Motion. Development of Game on Oculus VR. Animating the object in Unity

## What's next for CPR.VR

An Upgraded version where a user can perform the artificial ventilation and mouth to mouth ventilation at the right time after giving CPR

## Built With

* Adobe Fuse
* C#
* Leap Motion
* Mixamo
* [](https://devpost.com/software/built-with/oculus-gear-vr)Oculus Gear VR
* Unity

## Try it out

* [ GitHub Repo](https://github.com/sayakbiswas/hackriddle-2017 "https\://github.com/sayakbiswas/hackriddle-2017")