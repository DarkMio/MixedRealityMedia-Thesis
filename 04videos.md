---
title: 4. Video to Mixed Reality
anchor: v2mr
---

## 4.2 Camera Input Lag

{% include video.html video="time_aligned.mp4" title="With Time Drift Adjustment"
   description="After aligning frames the motion in engine and video capture are
   in sync"
%}

{% include video.html video="time_not_aligned.mp4" title="Without Time Drift Adjustment"
   description="Before video and engine frames have been aligned, there is a
   noticable difference in motion"
%}

## 4.7 Light Environment Reproduction

{% include video.html video="self-illu_new.mp4" title="VR actress illuminates herself with a virtual flashlight"
   description="A minor last step is light-reproduction, in which an approximate
   lightning setting will be transferred from 3D environment to the video feed
   of a VR actor. Assuming that the video footage contains a natural lit,
   tint-free and calibrated video signal, it is possible to approximate how a VR
   actor would be lit like if he truly is inside the virtual environment"
%}