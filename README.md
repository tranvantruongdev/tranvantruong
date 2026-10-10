# Tran Van Truong · playable CV

Live: https://tranvantruong.pages.dev

My CV as a small game: a pixel cyclist rides a stage profile where each climb is one stage of my career,
sized by time on the team. Below the ride is a plain, newest-first roadbook for anyone who'd rather read.

- Static `index.html` with CSS and vanilla JavaScript, no framework or build step; project previews are small local images loaded lazily, and the contact section links the email-only PDF candidate
- Canvas 2D renderer drawn at low resolution and scaled up for crisp pixel art; Bresenham lines and
  midpoint circles for the bike, simple physics for climbs and descents
- Keyboard and touch controls, auto-ride, light and dark themes, reduced-motion support
- All CV content lives in one `CV` object at the top of the script
- Hosted on Cloudflare Pages
