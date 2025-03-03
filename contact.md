---
layout: page
title: Contact Me
permalink: /contact/
---
<form action="https://formspree.io/f/your-email-here" method="POST" class="contact-form">
    <label for="name">Nama:</label>
    <input type="text" id="name" name="name" required>

    <label for="gender">Jenis Kelamin:</label>
    <select id="gender" name="gender" required>
        <option value="">Pilih Jenis Kelamin</option>
        <option value="Laki-laki">Laki-laki</option>
        <option value="Perempuan">Perempuan</option>
    </select>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="phone">Nomor Handphone:</label>
    <input type="tel" id="phone" name="phone" pattern="[0-9]+" required placeholder="Masukkan nomor telepon">
    
    <label for="subject">Judul Email:</label>
    <input type="text" id="subject" name="subject" required>

    <label for="message">Pesan:</label>
    <textarea id="message" name="message" rows="4" required></textarea>

    <button type="submit">Kirim</button>
</form>
