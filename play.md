---
layout: page
title: Fun Stuff
permalink: /play/
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
  <a href="#books-section">Bookshelf</a>
  <a href="#travel-section">Travels</a>
  <a href="#notes-section">Notes</a>
</nav>

<h2 id="books-section">📚 Bookshelf</h2>

Reading is a big part of my life. I started tracking the books I've read a few years ago, and I'll
try and list them in the order I've read them in. For now, as I build out this website, I've only kept a small version
of the list, just including the ones I recommend. 

### 2026
- James Clavell, *Shogun*
- Malala Yousafzai, *Finding My Way: A Memoir*

### 2025
- Fyodor Dostoyevsky, *The Brothers Karamazov*
- Robert K. Massie, *Catherine the Great* (gifted by a friend)
- Homer (Lombardo translation), *Iliad*
- Seneca, *Letters from a Stoic*
- Kenneth W. Ford, *The Quantum World – Quantum Physics for Everyone*

### 2024
- Viktor Frankl, *Man's Search for Meaning*
- Milan Kundera, *The Unbearable Lightness of Being*
- Khaled Hosseini, *A Thousand Splendid Suns*
- Brianna Wiest, *101 Essays That Will Change The Way You Think*
- Niccolò Machiavelli, *The Prince*
- Ishiguro Kazuo, *Never Let Me Go*
- Murasaki Shikibu, *The Tale of Genji*
- Ursula Le Guin, Books of Earthsea (a series)
- Cal Newport, *Deep Work*
- Marcus Aurelius, *Meditations*

### 2023

- George Orwell, *1984*
- Susanna Clarke, *Piranesi*
- Gabriel García Márquez, *100 Years of Solitude*

### High school and earlier

- Margaret Atwood, *The Handmaid’s Tale*
- Amor Towles, *A Gentleman in Moscow*
- Marjane Satrapi, *Persepolis*
- Khaled Hosseini, *The Kite Runner*

<hr>

<h2 id="travel-section">🌏 My Travels</h2>

<div class="travel-grid">
  <a href="#" class="travel-card">
    <span class="date">Dec 2025</span>
    <h3>Tokyo, Japan</h3>
    <p>Was never bored here—exiting every station felt like I was in a new world. 
    Fav areas: Shinjuku, Roppongi Hills, Ueno.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Dec 2025</span>
    <h3>Kyoto, Japan</h3>
    <p>Probably my favourite city in Japan—the mountains, shrines and history have my heart.
    Fav shrines: Chion-in temple, Kiyomizu Dera; special mention: Hachi shrine, stumbled upon here.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Oct 2024</span>
    <h3>Montreal, Canada</h3>
    <p>Maybe the best city in Canada. Loved the architecture—a blend of North America and France.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Aug 2024</span>
    <h3>Krakow, Poland</h3>
    <p>Was not destroyed during WWII. Every street felt like it had a story. Fav area: Kazimierz.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Aug 2019</span>
    <h3>Yerevan, Armenia</h3>
    <p>Got a haircut here, too. The city is set against the backdrop of Mt. Ararat!
    Loved walking around Republic Square at night. Memorable restaurant: Sherep.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Apr 2018</span>
    <h3>Baku, Azerbaijan</h3>
    <p>Will never forget walking around Icheri Sheher, and don’t forget to visit Ateshgah - 
    a fire temple meant for travellers on the Silk Road! Loved the kebabs!</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Apr 2017</span>
    <h3>Tblisi, Georgia</h3>
    <p>Located near the ancient Silk Road - explore ancient Asian cultures and its more-recent Soviet past. 
    Georgia is also very famous for its wines!</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Multiple</span>
    <h3>Kolkata, India</h3>
    <p>A vibrant city, known for its culture and literature. 
    Streets lined with bookstores and great street food!</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Aug 2018</span>
    <h3>Kathmandu, Nepal</h3>
    <p>A historic city, loved exploring the temples. 
    Try the momos on the street and visit Thamel Bazaar.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Aug 2016</span>
    <h3>Singapore</h3>
    <p>A green, well-connected city. Loved the multicultural identity 
    and how it continues to build around it.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Multiple</span>
    <h3>Shillong, India</h3>
    <p>India’s northeast is breathtaking. Located on the Eastern Himalayas’ foothills, 
    explore the state of Meghalaya. One of my fav places in India.</p>
  </a>

  <a href="#" class="travel-card">
    <span class="date">Multiple</span>
    <h3>Dubai, U.A.E.</h3>
    <p>Ever-changing. Experienced glitz and the old Middle East feel. Probably biased, because I lived there.</p>
  </a>
</div>

<h2 id="notes-section">📝 My Notes</h2>

### A collection of my musings and some notes, for future reference.

<div>
    <details>
        <summary><b>Notes from 7 Habits of Highly Effective People</b>
        <small>July 2025</small>
        </summary>
        <br>
        <ol>
        <li> Be proactive, not reactive. Stop saying "I have to" and start saying "I choose to." Sounds simple but it's a total mindset shift. You realize you have way more control over your responses than you think. </li>
        <li> Begin with the end in mind. Before jumping into any project or even your day, ask yourself what success looks like. I started doing this with meetings and it cut my time in half. </li>
        <li> Put first things first. The urgent/important matrix changed everything. Most "urgent" stuff isn't actually important, and most important stuff isn't urgent. Focus on important but not urgent tasks. </li>
        <li> Think win-win. Instead of trying to come out on top in every situation, look for solutions where everyone benefits. Made my workplace relationships way less stressful. </li>
        <li> Seek first to understand, then to be understood. Listen to actually understand, not just to respond. This one improved my relationships more than anything else. </li>
        <li> Synergize. Two people working together can achieve more than two people working separately. Sounds obvious but I was always trying to do everything myself. </li>
        <li> Sharpen the saw. Take care of yourself physically, mentally, emotionally, and spiritually. You can't pour from an empty cup. </li>
        </ol>
    </details>
</div>