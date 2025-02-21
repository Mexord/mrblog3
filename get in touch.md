---
layout: default
title: Get in Touch
permalink: /get-in-touch
---

# Kontaktformular

Wir freuen uns, von dir zu hören! Bitte fülle das Formular aus und wir werden uns so schnell wie möglich bei dir melden.

<form action="https://formspree.io/f/xyyojpla" method="POST">
  
  <label for="first-name">Vorname:</label><br>
  <input type="text" id="first-name" name="first-name" minlength="3" required><br><br>

  <label for="last-name">Nachname:</label><br>
  <input type="text" id="last-name" name="last-name" minlength="3" required><br><br>

  <label for="street">Straße:</label><br>
  <input type="text" id="street" name="street" minlength="3" required><br><br>

  <label for="house-number">Hausnummer:</label><br>
  <input type="text" id="house-number" name="house-number" required><br><br>

  <label for="city">Ort:</label><br>
  <input type="text" id="city" name="city" minlength="3" required><br><br>

  <label for="phone">Telefonnummer:</label><br>
  <input type="tel" id="phone" name="phone" pattern="^[0-9]{3,5}[ -]?[0-9]{6,}$" placeholder="Z.B. 030 12345678" required><br><br>

  <label for="email">E-Mail:</label><br>
  <input type="email" id="email" name="email" minlength="7" required><br><br>

  <label for="message">Nachricht:</label><br>
  <textarea id="message" name="message" rows="4" required></textarea><br><br>

  <button type="submit">Absenden</button>
</form>

<p>Alternativ kannst du uns auch direkt per E-Mail unter <a href="mailto:kontakt@magischer-verlag.de">kontakt@magischer-verlag.de</a> erreichen.</p>
