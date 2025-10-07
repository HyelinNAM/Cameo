# CAMEO: Generating Human Motion Videos using a Cascaded Text-to-Video Framework

This repository is the official implementation of Generating Human Motion Videos using a Cascaded Text-to-Video Framework. <br>
led by [Hyelin Nam](https://hyelinnam.github.io/)*, Hyojun Go, Byeongjun Park, Byung-Hoon Kim†, Hyungjin Chung†

[![Project Website](https://img.shields.io/badge/Project-Website-blue)](https://hyelinnam.github.io/Cameo/)
[![arXiv](https://img.shields.io/badge/arXiv-2510.03909-b31b1b.svg)](https://arxiv.org/abs/2510.03909)

<!-- <table class="center">
  <tr>
    <td style="text-align:center;"><b>Baseline</b></td>
    <td style="text-align:center;" colspan="1"><b>Ours</b></td>
  </tr>
  <tr>
    <td><img src="assets/0296-close-up-video-of-japanese-food.gif"></td>
    <td><img src="assets/0296-close-up-video-of-japanese-food-ours.gif"></td>
  </tr>
  <tr>
    <td><img src="assets/0456-person-dancing-in-a-dark-room.gif"></td>
    <td><img src="assets/0456-person-dancing-in-a-dark-room-ours.gif"></td>
  </tr>
</table> -->

## Abstract
Human video generation is becoming an increasingly important task with broad applications in graphics, entertainment, and embodied AI. Despite the rapid progress of video diffusion models (VDMs), their use for general-purpose human video generation remains underexplored, with most works constrained to image-to-video setups or narrow domains like dance videos. In this work, we propose CAMEO, a cascaded framework for general human motion video generation. It seamlessly bridges Text-to-Motion (T2M) models and conditional VDMs, mitigating suboptimal factors that may arise in this process across both training and inference through carefully designed components. Specifically, we analyze and prepare both textual prompts and visual conditions to effectively train the VDM, ensuring robust alignment between motion descriptions, conditioning signals, and the generated videos. Furthermore, we introduce a camera-aware conditioning module that connects the two stages, automatically selecting viewpoints aligned with the input text to enhance coherence and reduce manual intervention. We demonstrate the effectiveness of our approach on both the MovieGen benchmark and a newly introduced benchmark tailored to the T2M-VDM combination, while highlighting its versatility across diverse use cases.
