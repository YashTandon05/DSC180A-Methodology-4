---
layout: default
title: Methodology Assignment 4
---

# Methodology Assignment 4

**Name:** Yash Tandon
**UCSD email:** ytandon@ucsd.edu
**Section:** D38
**Mentor:** Prof. Zhijian Liu

**1. What is the most interesting topic covered in your domain this quarter?**  
I think for me the most interesing has been Image/Video Generation, especially the concept of flow matching. I'm really interested in robotics, thus, I've recently started working with VLAs. One of the most important part of the VLA is efficient, yet reliable generation of action chunks, thus flow matching is used to effectively denoise a random initialization into a correct output. I wasn't familiar that this technique is also used for generative AI.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
On top of Quantization, I feel like it would be valuable to run experiments with other speed-up methods like speculative decoding, and especially flow matching. We are working with VLAs, and flow matching looks really promising. The only issue is that the field is very saturated in the flow matching space, but I'm confident we can find some valuable insights.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
For the current quarter's project, we're just trying to recreate the quantization approaches taken by other teams. However, we've noticed that those methods aren't very effective (either decrease accuracy a lot, or instead increase the inference time due to overhead from switching precisions). This is valuable, but it would also be great to have the environment set up for our own custom quantization methods like regime-aware quantization.

**4. What other techniques would you be interested in using in your project?**  
Speculative-decoding, Model distilling, DFlash-block drafter for FAST, Flow Matching
