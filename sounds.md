---
layout: page
permalink: /sounds/
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Sounds</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      background: #fff;
      margin: 0;
      padding: 0;
      font-family: system-ui, sans-serif;
    }
    .container {
      max-width: 900px;
      margin: 2.5rem auto;
      padding: 0 1rem;
    }
    .sounds-tiles {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .sounds-tiles a {
      flex: 1 1 calc(33.333% - 1rem);
      max-width: calc(33.333% - 1rem);
      min-width: 0;
      background: #f9f9f9;
      border-radius: 16px;
      border: 1.5px solid #111;
      overflow: hidden;
      display: flex;
      align-items: stretch;
      transition: box-shadow 0.3s, transform 0.3s;
      text-decoration: none;
    }
    .sounds-tiles a:hover,
    .sounds-tiles a:focus {
      z-index: 2;
      box-shadow: 0 4px 12px rgba(0,0,0,0.13);
      transform: scale(1.03);
    }
    .sounds-tiles .sound-tile-inner {
      width: 100%;
      aspect-ratio: 1/1;
    }
    @media (max-width: 600px) {
      .sounds-tiles a {
        flex: 1 1 100%;
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="sounds-tiles">
      <a href="https://www.ekr.blog/soundscapes/An%20Alley%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Birds%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Buses%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Cafes%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Drain%20(Canada).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Izakaya%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Konbini%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/River%20(Canada).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Stations%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Streams%20(Canada).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Waves%20(Japan).mp3"><div class="sound-tile-inner"></div></a>
      <a href="https://www.ekr.blog/soundscapes/Restaurant%20(Japan).mp3"><
