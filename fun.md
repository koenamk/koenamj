---
layout: page
title: Fun Stuff
permalink: /fun/
---

<style>
  html {
    scroll-behavior: smooth;
  }

  /* Sticky Navigation with Glassmorphism */
  .sticky-nav {
    position: -webkit-sticky; 
    position: sticky;
    top: 0;
    /* Semi-transparent background */
    background: rgba(255, 255, 255, 0.8); 
    /* The Blur Effect */
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    
    padding: 15px 0;
    border-bottom: 1px solid rgba(0, 0, 0, 0.05);
    z-index: 1000;
    display: flex;
    gap: 15px;
    font-size: 0.9rem;
    margin-bottom: 20px;
  }

  .sticky-nav span {
    color: #999;
    font-weight: bold;
    text-transform: uppercase;
    font-size: 0.75rem;
    letter-spacing: 1px;
  }

  .sticky-nav a {
    text-decoration: none;
    color: #2e8b57;
    font-weight: 600;
    transition: color 0.2s;
  }

  .sticky-nav a:hover {
    color: #1b5e38;
  }

  /* Prevent headers from hiding under the sticky bar when jumping */
  h2[id] {
    scroll-margin-top: 80px;
    margin-top: 40px;
  }

  /* The Grid Container */
  .travel-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }

  /* The Card Design */
  .travel-card {
    background: #fdfdfd;
    border: 1px solid #eee;
    border-radius: 12px;
    padding: 20px;
    text-decoration: none;
    color: inherit !important; /* Prevents Jekyll link colors */
    transition: all 0.3s ease;
    display: block;
  }

  .travel-card:hover {
    transform: translateY(-5px);
    border-color: #2e8b57;
    background-color: #f7f9f8; 
    filter: hue-rotate(15deg) saturate(1.2);
    box-shadow: 0 10px 20px rgba(0,0,0,0.05);
  }

  .travel-card h3 { margin: 0 0 10px 0; font-size: 1.1rem; }
  .travel-card p { font-size: 0.85rem; color: #666; line-height: 1.5; margin: 0; }
  .travel-card .date { font-size: 0.7rem; color: #aaa; display: block; margin-bottom: 5px; }
</style>

<nav class="sticky-nav">
  <span>Jump to:</span>
  <a href="#books-section">Readings</a>
  <a href="#travel-section">Travels</a>
</nav>

<h2 id="books-section">📚 Readings</h2>

Reading is a big part of my life. I started tracking the books I've read a few years ago, and I'll
try and list them in the order I've read them in. For now, as I built out this website, I've only kept a small version
of the list, just including the ones I recommend. 

### 2026
- Shogun by James Clavell

### 2025
- Iliad, by Homer (Lombardo translation) 
- The Quantum World – Quantum Physics for Everyone by Kenneth W. Ford

### 2024
- Man's Search for Meaning, by Viktor Frankl
- The Unbearable Lightness of Being, by Milan Kundera
- A Thousand Splendid Suns, by Khaled Hosseini
- 101 Essays That Will Change The Way You Think, by Brianna Wiest
- The Prince, by Niccolò Machiavelli
- Never Let Me Go, by Kazuo Ishiguro
- The Tale of Genji, by Murasaki Shikibu
- Books of Earthsea, by Ursula Le Guin

<hr>

<h2 id="travel-section">🌏 My Travels</h2>

<div class="travel-grid">
  <a href="#" class="travel-card">
    <span class="date">Dec 2025</span>
    <h3>Tokyo, Japan</h3>
    <p>Was never bored here—exiting every station felt like I was in a new world. Fav areas: Shinjuku, Roppongi Hills.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Dec 2025</span>
    <h3>Kyoto, Japan</h3>
    <p>Probably my favourite city in Japan—the mountains, shrines and history have my heart.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Oct 2024</span>
    <h3>Montreal, Canada</h3>
    <p>Maybe the best city in Canada. Loved the architecture—a blend of N. America and France.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Aug 2024</span>
    <h3>Krakow, Poland</h3>
    <p>Was not destroyed during WWII. Every street felt like it had a story. Fav area: Kazimierz.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Aug 2019</span>
    <h3>Yerevan, Armenia</h3>
    <p>Got a haircut here, too. Loved walking around Republic Square at night. Memorable restaurant: Sherep.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Multiple</span>
    <h3>Kolkata, India</h3>
    <p>A vibrant city, known for its culture and literature. Streets lined with bookstores and great street food!</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Aug 2018</span>
    <h3>Kathmandu, Nepal</h3>
    <p>A historic city, loved exploring the temples. Try the momos on the street and visit Thamel Bazaar.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Dec 2025</span>
    <h3>Singapore</h3>
    <p>A green, well-connected city. Loved the multicultural identity and how it continues to build around it.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Multiple</span>
    <h3>Dubai, U.A.E.</h3>
    <p>Ever-changing. Experienced glitz and the old Middle East feel. Probably biased, because I lived there.</p>
  </a>
</div>