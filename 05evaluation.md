---
title: 5. Evaluation & Conclusion
anchor: eval
---

## 5.4 Edge Cases


{% include video.html video="z-clipping.mp4" title="Incorrect Z Calculation for Hands"
   description="Due to the planar projection of the real world feed inside the
   engine, any Z- information of the actor is squashed to a fixed depth.
   This means that hands are on the same plane. In cases with high z-difference
   between actor and actor’s hands, it is possible that hand motion look
   unnatural and does not seem like it is to be supposed — the actors hands are
   clearly in front of a virtual cube. The produced mixed reality image shows
   his arms only behind the cube."
%}

{% include video.html video="blur_new.mp4" title="5.4.2 Matting Failures (Blur) - new"
   description="real time chroma keying has problems with motion blur of the
   source video material — causing background mixing and incorrect matting.
   This is a complex problem that is far beyond the scope of this thesis."
%}

{% include video.html video="blur_old.mp4" title="5.4.2 Matting Failures (Blur) - old"
%}