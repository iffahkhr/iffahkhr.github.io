<div class="contact-container">
    <h2>Contact Me</h2>
    <form class="contact-form" action="proses.php" method="POST">
        <label for="name">Nama:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Nomor HP:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="gender">Jenis Kelamin:</label>
        <select id="gender" name="gender">
            <option value="Laki-laki">Laki-laki</option>
            <option value="Perempuan">Perempuan</option>
        </select>

        <label for="title">Judul Pesan:</label>
        <input type="text" id="title" name="title" required>

        <label for="message">Isi Pesan:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Kirim</button>
    </form>
</div>
