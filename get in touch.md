---
layout: default
title: Get in Touch
permalink: /get-in-touch
---

# Kontaktformular

Wir freuen uns, von dir zu hören! Bitte fülle das Formular aus und wir werden uns so schnell wie möglich bei dir melden.

<form action="https://formspree.io/f/xyyojpla" method="POST">
  
  <!-- Vorname (mindestens 3 Zeichen) -->
  <label for="first-name">Vorname:</label><br>
  <input type="text" id="first-name" name="first-name" minlength="3" required><br><br>

  <!-- Nachname (mindestens 3 Zeichen) -->
  <label for="last-name">Nachname:</label><br>
  <input type="text" id="last-name" name="last-name" minlength="3" required><br><br>

  <!-- Straße (mindestens 3 Zeichen) -->
  <label for="street">Straße:</label><br>
  <input type="text" id="street" name="street" minlength="3" required><br><br>

  <!-- Hausnummer -->
  <label for="house-number">Hausnummer:</label><br>
  <input type="text" id="house-number" name="house-number" required><br><br>

  <!-- Ort (mindestens 3 Zeichen) -->
  <label for="city">Ort:</label><br>
  <input type="text" id="city" name="city" minlength="3" required><br><br>

  <!-- Telefonnummer (mindestens 9 Zahlen, deutsche Formatierung) -->
  <label for="phone">Telefonnummer:</label><br>
  <input type="tel" id="phone" name="phone" pattern="[0-9]{9,}" placeholder="Z.B. 0301234567" required><br><br>

  <!-- E-Mail (mindestens 7 Zeichen) -->
  <label for="email">E-Mail:</label><br>
  <input type="email" id="email" name="email" minlength="7" required><br><br>

  <!-- Nachricht (mindestens 150 Zeichen) -->
  <label for="message">Nachricht:</label><br>
  <textarea id="message" name="message" rows="4" minlength="150" required></textarea><br><br>

  <button type="submit">Absenden</button>
</form>

<p>Alternativ kannst du uns auch direkt per E-Mail unter <a href="mailto:kontakt@magischer-verlag.de">kontakt@magischer-verlag.de</a> erreichen.</p>
