---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: A Crossed Arm Voxel Network for Humanoid Robot-Human Interaction in Magic Performances
info: 

# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
# duration of the presentation
duration: 15min
---

# GA Crossed Arm Voxel Network for Humanoid Robot-Human Interaction in Magic Performances

  ## *Hanjaya Mandala*,  *Saeed Saeedvand*,  *Jacky Baltes*,  National Taiwan Normal University, Taiwan\    
  <jacky.baltes@ntnu.edu.tw>

  
<div style="
  position: absolute;
  top: 2px;
  right: 0px;
  z-index: 1000;
">
  <a href="/export/">
    <img src="/button-1.png" alt="Download as PDF" style="width: 250px; border: none; cursor: pointer;">
  </a>
</div>


<!--
Notes
-->

---
transition: slide-left
---
<style>
.slidev-layout {
  font-size: 2rem;
}
</style>

# Introduction

- **Magic as a robotics testbed**: Magic tricks demand real-time vision, precise manipulation, and human-robot interaction, making them an ideal benchmark for humanoid robots.

- **Hidden Coin trick**: When people cross their arms hiding a coin, they instinctively place the coin hand underneath, a psychological tendency validated at 92% accuracy on 50 individuals.

- **Fully autonomous**: The robot executes the entire trick [perception, decision, and pointing] without human assistance.

---
layout: center
---

Chris Ramsay (Famous Magician) 

<img src="/coin-magic-1.png"/>

---
---
# Which hand is the coin in?

- <img src="/coin-magic-2.png" width="700"/>

---
---
# Data Flow

- <img src="/coin-magic-3.png" width="700"/>

---
---
# System Overview

- <img src="/coin-magic-4.png" width="700"/>

---
---
# System Overview

- <img src="/coin-magic-5.png" width="700"/>

---
---
# Methodojogy

- <img src="/coin-magic-6.png" width="700"/>

---
---
# Methodology

- <img src="/coin-magic-7.png" width="700"/>

---
---
# Results

- <img src="/coin-magic-8.png" width="700"/>

---
---
# Results

- <img src="/coin-magic-9.png" width="700"/>

---
---
# Demo

<Youtube id="DHmVreM2pRY" width="700" height="500"/>
---
---
# Conclusion

- CAVN: 3D voxel network achieving 94% accuracy on crossed-arm classification from LiDAR data

- Publicly released dataset of 2000 labeled 3D crossed-arm scans (Hugging Face)

- Won 1st place at IROS 2019 HRAC Robot Magic & Music Competition (The Venetian, Macao)



---
transition: slide-left
layout: end
---
# Thanks
