---
layout: home
#title: Esteban Dal Monte - Music Producer
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700;800&display=swap');

.custom-header {
    background: linear-gradient(to bottom, #1a1a1a, #2d2d2d);
    padding: 3rem 0;
    margin: 0;
    text-align: center;
    width: 100vw;
    position: relative;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
    margin-top: -2rem; /* Remove top white space */
    margin-bottom: 3rem; /* Add spacing */
}

.custom-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 3.8em;
    font-weight: 600;
    letter-spacing: 0.03em;
    color: transparent;
    background: linear-gradient(45deg, #ffffff, #d4d4d4);
    -webkit-background-clip: text;
    background-clip: text;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
    margin: 0;
    text-transform: uppercase;
}

.subtitle {
    color: #ffffff;
    font-family: 'Montserrat', sans-serif;
    font-weight: 800;
    font-size: 1.2em;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin-top: 0.5em;
}

.elegant-heading {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    text-align: center;
    font-size: 1.5em;
    margin: 4rem 0;
}

.fire-heading {
    background: linear-gradient(45deg, #ff4d4d, #f9cb28);
    -webkit-background-clip: text;
    color: transparent;
    position: relative;
    animation: fire 6s ease-in-out infinite;
}

@keyframes fire {
    0% { text-shadow: 0 0 20px rgba(255,77,77,0.3); }
    50% { text-shadow: 0 0 40px rgba(249,203,40,0.5); }
    100% { text-shadow: 0 0 20px rgba(255,77,77,0.3); }
}

.contact-section {
    text-align: center;
    margin: 4rem auto;
    max-width: 800px;
}

.cta-button {
    display: inline-block;
    padding: 20px 40px;
    font-size: 1.5em;
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    color: #ffffff;
    background: linear-gradient(45deg, #ff4d4d, #f9cb28);
    border-radius: 12px;
    text-decoration: none;
    margin: 2rem 0;
    transition: transform 0.3s;
}

.cta-button:hover {
    transform: translateY(-5px);
}

.social-icons {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin: 2rem auto;
}

.social-icon {
    width: 40px;
    height: 40px;
    opacity: 0.7;
    transition: opacity 0.3s;
}

.social-icon:hover {
    opacity: 1;
}

.elegant-text {
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Helvetica Neue", Arial, sans-serif;
    font-size: 1.1em;
    line-height: 1.8;
    letter-spacing: 0.01em;
    color: #2c3e50;
    margin: 0 auto;
    padding: 0 20px;
}

.profile-container .elegant-text {
    max-width: 100%;
    flex-grow: 1;
}

.profile-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
    max-width: 2100px;
    margin: 2rem auto;
    padding: 0 20px;
}

.profile-image {
    flex-shrink: 0;
    width: 1000px;
    height: 700px;
    border-radius: 4px; /* Match other images */
    object-fit: cover;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.image-grid-games {
    display: grid;
    grid-template-columns: repeat(3, 230px);
    justify-content: center;
    align-items: center;
    gap: 4px;
    margin: 2em auto;
    padding: 0 30px;
}

.image-grid-games img {
    width: 280px;
    height: 260px;
    object-fit: cover;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.image-grid img {
    width: 1600px;
    height: 390px;
    object-fit: cover;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.music-grid {
    position: relative;
    margin: 4rem auto;
    padding: 3rem 0;
    max-width: 2100px;
}

.music-grid > * {
    position: relative;
    z-index: 1;
}

.music-grid, .games-grid, .profile-container, .image-grid {
    margin: 4rem auto;
}

.video-container {
    margin-bottom: 4rem;
}

/* Mobile Responsive Styles */
@media screen and (max-width: 768px) {
    .custom-title {
        font-size: 2.5em;
    }

    .subtitle {
        font-size: 1.2em;
    }

    .elegant-heading {
        font-size: 2em;
        margin: 2rem 0;
    }

    .profile-container {
        flex-direction: column;
        gap: 2rem;
    }

    .profile-images {
        width: 100%;
    }

    .profile-image {
        width: 100%;
        height: auto;
        max-width: 350px;
        margin: 0 auto;
    }

    .music-grid {
        grid-template-columns: 1fr;
        gap: 15px;
    }

    .games-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 15px;
    }

    .game-image {
        height: 150px;
    }

    .image-grid img {
        width: 100%;
        height: auto;
        max-width: 350px;
    }

    .social-icons {
        gap: 20px;
        align-items: center;
    }

    .social-icon {
        width: 50px;
        height: 50px;
        aspect-ratio: 1/1;
        object-fit: contain;
        display: block;
    }

    .elegant-text {
        font-size: 1.2em;
        line-height: 1.6;
    }
}
</style>

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<script>
document.addEventListener('DOMContentLoaded', function() {
    const observer = new IntersectionObserver(
        (entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        },
        { threshold: 0.5 }
    );

    const fireHeading = document.querySelector('.fire-heading');
    observer.observe(fireHeading);
});
</script>

<div class="custom-header">
    <h1 class="custom-title">Esteban Dal Monte</h1>
    <div class="subtitle">
        Music Producer & Technical Sound Designer
    </div>
    <!--div style="margin-top: 1rem;">
        <a href="/resume/" style="color: #ffffff; text-decoration: none; font-family: 'Montserrat', sans-serif; font-size: 1em;">View Resume</a>
    </div-->
</div>

<!-- Video -->
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
          src="https://www.youtube.com/embed/R795M_7b26M?si=Bx0p49G4guD1ItgZ" 
          title="Reel" 
          frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
  </iframe>
</div>

<h2 class="elegant-heading">About me</h2>
<div class="profile-container">
    <img src="/images/StudioStanding.jpg" alt="Profile Photo" class="profile-image">
    <div class="elegant-text">
        <p>I'm a Music Producer and Technical Sound Designer with over a decade of experience in the games and media industry.</p>
        <p>My unique background combines music production with hands-on experience as a programmer and game designer, having completed more than 15 successful projects.</p>
        <p>Now fully dedicated to music production in my personal studio, I bring a creativity-centered approach to every project I take on, blending my technical expertise with artistic vision to create new soundscapes.</p>
    </div>
</div>

<h2 class="elegant-heading">Projects</h2>
<div class="image-grid-games">
    <img src="/images/dragonwars.jpg" alt="KR5">
    <img src="/images/shipMiner2cropped.png" alt="Ship Miner">
    <img src="/images/cleanupcapsule.jpg" alt="Cleanup Capsule">
    <img src="/images/Iron Marines.jpg" alt="Iron Marines">
    <img src="/images/bonsai.png" alt="Bonsai">
    <img src="/images/aconcagua3.jpg" alt="Aconcagua">
    <img src="/images/superscaloni.png" alt="Super Scaloni">
    <img src="/images/titans.png" alt="Titans">
    <img src="/images/airborne.jpg" alt="Airborne">
</div>

<h2 class="elegant-heading">Featured Music</h2>
<div class="music-grid">
<div class="elegant-text" style="text-align: center;">
  <div style="margin-bottom: 30px;">
    <p style="color: #7f8c8d; font-size: 0.9em;">Click play to listen or visit <a href="https://soundcloud.com/dalmontemusic" target="_blank" style="color: #ff5500;">SoundCloud</a> for more</p>
  </div>

  <iframe width="100%" 
          height="120" 
          scrolling="no" 
          frameborder="no" 
          allow="autoplay" 
          src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1499376376&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true">
  </iframe>

  <iframe width="100%" 
          height="120" 
          scrolling="no" 
          frameborder="no" 
          allow="autoplay"
          style="margin-top: 20px;" 
          src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1661129973&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true">
  </iframe>

  <iframe width="100%" 
          height="120" 
          scrolling="no" 
          frameborder="no" 
          allow="autoplay"
          style="margin-top: 20px;" 
          src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1854610773&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true">
  </iframe>

  <iframe width="100%" 
          height="120" 
          scrolling="no" 
          frameborder="no" 
          allow="autoplay"
          style="margin-top: 20px;" 
          src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1436891956&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true">
  </iframe>
  
</div>

<div class="image-grid">
    <img src="/images/StudioPlaying.jpg" alt="Studio Playing">
</div>

<h2 class="elegant-heading fire-heading">Let's Work Together</h2>

<div class="contact-section">
  
    
    <div class="social-icons">
        <a href="mailto:correoesti@outlook.com">
            <img src="https://cdn-icons-png.flaticon.com/512/552/552486.png" alt="Email" class="social-icon">
        </a>
        <a href="https://soundcloud.com/dalmontemusic" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/145/145809.png" alt="SoundCloud" class="social-icon">
        </a>
        <a href="https://linkedin.com/in/dalmonteroquero" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/145/145807.png" alt="LinkedIn" class="social-icon">
        </a>
        <a href="https://instagram.com/unf0ldmusic" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" class="social-icon">
        </a>
        <a href="https://www.youtube.com/channel/UCdgMWDm_3oJD4xYIaosaR_w" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="YouTube" class="social-icon">
        </a>
    </div>
</div>