---
layout: post
title: "My Room in Year 4 at VinUni"
date: 2026-06-24 00:00:00
description: A 360-degree view of my room before moving out of Hanoi.
tags: memories vinuni hanoi
categories: personal
---

A 360-degree view of my room before moving out. Goodbye Hanoi—I'm not sure when I'll be back next, and it's even harder to know when or for what reason I will stay in Hanoi for such a long time again in the future.

<!-- Pannellum 360-degree panorama viewer -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/pannellum@2.5.6/build/pannellum.css"/>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/pannellum@2.5.6/build/pannellum.js"></script>

<div id="panorama" style="display:block; width:90%; height:500px; margin:20px auto; max-width:880px; border-radius:8px; border:0 none; box-shadow: 0 1px 1px rgba(0,0,0,0.11),0 2px 2px rgba(0,0,0,0.11),0 4px 4px rgba(0,0,0,0.11),0 6px 8px rgba(0,0,0,0.11),0 8px 16px rgba(0,0,0,0.11);"></div>

<script>
(function () {
  function initPanorama() {
    pannellum.viewer('panorama', {
      type: 'equirectangular',
      panorama: "{{ '/assets/img/year4_room_360.jpg' | relative_url }}",
      autoLoad: true,
      compass: false,
      hfov: 110,
    });
  }

  if (typeof pannellum !== 'undefined') {
    initPanorama();
  } else {
    document.querySelector('script[src*="pannellum.js"]').addEventListener('load', initPanorama);
  }
})();
</script>
