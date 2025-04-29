---
layout: default
permalink: /
---

{% if site.dev_mode %}
The guild of the Dungeon Masters are plotting!
{% else %}
<section class="hero">
  <div class="hero-container">
    <div class="hero-logo-container">
      <img src="{{ '/assets/images/logo.svg' | relative_url }}" alt="The House of Adventures Logo" class="hero-logo">
    </div>
    <div class="hero-content">
      <h2>WELCOME TO OUR COMMUNITY</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed commodo eu est sed ullamcorper. Mauris varius venenatis molestie. Morbi tinci</p>
      
      <div class="hero-buttons">
        <a href="{{ site.discord }}" class="btn btn-discord" target="_blank" rel="noopener noreferrer">Discord</a>
        <a href="{{ site.whatsapp }}" class="btn btn-whatsapp" target="_blank" rel="noopener noreferrer">Whatsapp</a>
        <a href="{{ site.instagram }}" class="btn btn-instagram" target="_blank" rel="noopener noreferrer">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" style="width: 20px; height: 20px; color: white;">
            <path fill="currentColor" d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"/>
          </svg>
        </a>
      </div>
    </div>
  </div>
</section>

<section class="section who-are-we">
  <div class="section-container">
    <div class="section-text">
      <h2>WHO ARE WE</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed commodo eu est sed ullamcorper. Mauris varius venenatis molestie. Morbi tinci</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed commodo eu est sed ullamcorper. Mauris varius venenatis molestie. Morbi tinci</p>
    </div>
    <div class="section-images image-grid">
      <div class="section-image-placeholder"></div>
      <div class="section-image-placeholder"></div>
      <div class="section-image-placeholder large"></div>
    </div>
  </div>
</section>

<section class="section what-we-do">
  <div class="section-container">
    <div class="section-images">
      <img src="{{ '/assets/images/discord-embed.png' | relative_url }}" alt="Discord Embed" class="discord-embed-img">
    </div>
    <div class="section-text">
      <h2>WHAT WE DO</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed commodo eu est sed ullamcorper. Mauris varius venenatis molestie. Morbi tinci</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed commodo eu est sed ullamcorper. Mauris varius venenatis molestie. Morbi tinci</p>
    </div>
  </div>
</section>
{% endif %}

<style>
/* .btn-instagram {
  background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
  width: 44px;
  padding: 0;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  aspect-ratio: 1/1;
} */
</style>