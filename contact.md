---
layout: page
title: Contact Me
permalink: /contact/
---

<h2>Contact Me</h2>

<form action="https://formspree.io/f/your-form-id" method="POST">
    <label for="name">Nama:</label><br>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="phone">Nomor HP:</label><br>
    <input type="tel" id="phone" name="phone" required><br><br>

    <label for="gender">Jenis Kelamin:</label><br>
    <select id="gender" name="gender">
        <option value="Laki-laki">Laki-laki</option>
        <option value="Perempuan">Perempuan</option>
    </select><br><br>

    <button type="submit">Kirim</button>
</form>
