+++
widget = "people"
headless = true
active = true
weight = 70
title = ""
+++

<style>
.group-photo-wrapper {
  /* The "Safe" Breakout Method */
  width: 100vw;
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  
  text-align: center;
  padding: 40px 20px;
  box-sizing: border-box; /* Prevents padding from causing scrollbars */
}

.group-photo-wrapper img {
  max-width: 1000px; /* Limit width so it doesn't fill 4k screens */
  width: 100%;
  height: auto;
  border-radius: 12px;
  display: inline-block; /* Helps with centering in this specific wrapper */
}

.group-photo-wrapper p {
  margin-top: 12px;
  color: #666;
}
</style>

<div class="group-photo-wrapper">
  <img src="/img/groupPhoto.jpg" alt="Group Photo">
  <p><em>Our team (2025)</em></p>
</div>