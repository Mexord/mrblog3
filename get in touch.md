---
layout: default
title: Get in Touch
permalink: /get in touch
---

# Kontaktformular

Wir freuen uns, von dir zu hören! Bitte fülle das Formular aus und wir werden uns so schnell wie möglich bei dir melden.

<form action="https://formspree.io/f/xyyojpla" method="POST">
  
  <!-- Vorname -->
  <label for="first-name">Vorname:</label><br>
  <input type="text" id="first-name" name="first-name" required><br><br>

  <!-- Nachname -->
  <label for="last-name">Nachname:</label><br>
  <input type="text" id="last-name" name="last-name" required><br><br>

  <!-- E-Mail -->
  <label for="email">E-Mail:</label><br>
  <input type="email" id="email" name="email" required><br><br>

  <!-- Straße -->
  <label for="street">Straße:</label><br>
  <input type="text" id="street" name="street" required><br><br>

  <!-- Hausnummer -->
  <label for="house-number">Hausnummer:</label><br>
  <input type="text" id="house-number" name="house-number" required><br><br>

  <!-- Ort -->
  <label for="city">Ort:</label><br>
  <input type="text" id="city" name="city" required><br><br>

  <!-- Telefonnummer -->
  <label for="phone">Telefonnummer:</label><br>
  <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" placeholder="z.B. 123-456-7890" required><br><br>

  <!-- Nachricht -->
  <label for="message">Nachricht:</label><br>
  <textarea id="message" name="message" rows="4" required></textarea><br><br>

  <button type="submit">Absenden</button>
</form>

<p>Alternativ kannst du uns auch direkt per E-Mail unter <a href="mailto:kontakt@magischer-verlag.de">kontakt@magischer-verlag.de</a> erreichen.</p>
