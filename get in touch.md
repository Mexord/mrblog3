---
layout: default
title: Kontaktformular
permalink: /get in touch
---

<article class="post-container post-container--single">
  <header class="post-header">
    <h1 class="post-title">Kontaktformular</h1>
  </header>

  <section class="post">
    <form action="https://formspree.io/f/xyyojpla" method="POST">
  
      <!-- Vorname und Nachname -->
      <label for="first-name">Vorname:</label><br>
      <input type="text" id="first-name" name="first-name" required><br><br>

      <label for="last-name">Nachname:</label><br>
      <input type="text" id="last-name" name="last-name" required><br><br>

      <!-- Straße und Hausnummer -->
      <label for="street">Straße:</label><br>
      <input type="text" id="street" name="street" required><br><br>

      <label for="house-number">Hausnummer:</label><br>
      <input type="text" id="house-number" name="house-number" required><br><br>

      <!-- Telefonnummer -->
      <label for="phone">Telefonnummer:</label><br>
      <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" placeholder="z.B. 123-456-7890"><br><br>

      <!-- E-Mail -->
      <label for="email">E-Mail:</label><br>
      <input type="email" id="email" name="email" required><br><br>

      <!-- Nachricht -->
      <label for="message">Nachricht:</label><br>
      <textarea id="message" name="message" rows="4" minlength="150" required></textarea><br><br>

      <button type="submit">Absenden</button>
    </form>
  </section>
</article>
