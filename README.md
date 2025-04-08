<!DOCTYPE html>
<html lang="id">
<head>
	<meta charset="UTF-8">
	<title>Tugas Grafika Komputer PTI</title>
	<style>
		body {
			margin: 0;
			font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
			background-color: #ffe4ec;
			color: #5a2b3f;
		}

		header {
			background-color: #f8b4d9;
			color: white;
			padding: 30px 20px;
			text-align: center;
			box-shadow: 0 4px 8px rgba(0,0,0,0.1);
		}

		header h1 {
			background-color: rgba(255, 182, 193, 0.7);
			display: inline-block;
			padding: 10px 20px;
			border-radius: 20px;
		}

		ul {
			display: flex;
			justify-content: center;
			list-style-type: none;
			padding: 0;
			background-color: #f472b6;
			margin: 0;
		}

		ul li {
			margin: 0 15px;
		}

		ul li a {
			display: block;
			padding: 14px 20px;
			text-decoration: none;
			color: white;
			font-weight: bold;
			transition: background-color 0.3s;
		}

		ul li a:hover {
			background-color: #ec4899;
			border-radius: 10px;
		}

		section {
			padding: 30px;
			max-width: 800px;
			margin: auto;
			background-color: #fff0f6;
			box-shadow: 0 0 15px rgba(255,182,193,0.5);
			border-radius: 20px;
			margin-top: 30px;
		}

		section p {
			margin-bottom: 30px;
			padding: 20px;
			background-color: #ffd1dc;
			border-left: 6px solid #f472b6;
			border-radius: 12px;
			position: relative;
		}

		section p img.task-icon {
			position: absolute;
			right: 10px;
			top: 10px;
			width: 50px;
			opacity: 0.9;
		}

		section a {
			color: #d63384;
			text-decoration: none;
			display: inline-block;
			margin-top: 8px;
			font-weight: bold;
		}

		section a:hover {
			text-decoration: underline;
		}

		footer {
			text-align: center;
			padding: 20px;
			background-color: #ffc9de;
			margin-top: 40px;
			font-size: 0.9em;
			color: #7c3f58;
			border-top: 1px solid #f472b6;
		}

		.profil {
			display: flex;
			flex-direction: column;
			align-items: center;
			background-color: #ffe0f0;
			padding: 30px;
			border-radius: 20px;
			margin-top: 40px;
			box-shadow: 0 0 12px rgba(255,182,193,0.4);
		}

		.profil img {
			width: 150px;
			height: 150px;
			border-radius: 50%;
			object-fit: cover;
			border: 4px solid #f472b6;
			box-shadow: 0 4px 10px rgba(0,0,0,0.1);
		}

		.profil h2 {
			margin-top: 15px;
			color: #d63384;
		}

		.profil p {
			text-align: center;
			max-width: 500px;
			color: #6b3a4d;
		}
	</style>
</head>

<body>
	<header>
		<h1>Grafika Komputer<br>Syifa Nur Ramadhani</h1>
	</header>

	<ul>
		<li><a href="#">Beranda</a></li>
		<li><a href="#profil">Profil</a></li>
		<li><a href="#">Tentang</a></li>
	</ul>	

	<section id="profil" class="profil">
		<img src="Foto/Syifa.jpg" alt="Foto Profil">
		<h2>Syifa Nur Ramadhani</h2>
        <h2>NPM: 2413025019</h2>
		<p>Halo! Saya mahasiswa PTI yang sedang mempelajari mata kuliah Grafika Komputer. Di halaman ini, kamu bisa melihat berbagai tugas saya yang dikumpulkan dalam bentuk laporan PDF dan video. Terima kasih telah berkunjung! 💗</p>
	</section>

	<section>
		<p><strong>Tugas 1</strong>
			<br><a href="files/Tokoh.pdf">Laporan PDF</a>
			<br><a href="https://drive.google.com/file/d/1soPdPBa1z7QB9YSMwwnTabk5bIzRCH7L/view?usp=drive_link">Video</a>
			<img class="task-icon" src="https://i.imgur.com/d1HnQvN.png" alt="bunga">
		</p>

		<p><strong>Tugas 2</strong>
			<br><a href="files/Garis.pdf">Laporan PDF</a>
			<br><a href="https://drive.google.com/file/d/1x7bre_0bLeULsWzrROsYovoMSrDoukmq/view?usp=sharing">Video</a>
			<img class="task-icon" src="https://i.imgur.com/FNR0e7M.png" alt="hati">
		</p>

		<p><strong>Tugas 3</strong>
			<br><a href="files/Lingkaran.pdf">Laporan PDF</a>
			<br><a href="https://drive.google.com/file/d/197DhXJC35zZmnLEX766WZGcuJ0jb4nkw/view?usp=drive_link">Video</a>
			<img class="task-icon" src="https://i.imgur.com/Z4RIdFF.png" alt="bintang">
		</p>
	</section>

	<footer>
		<p>Hak Cipta &copy; Syifa Nur Ramadhani</p>
	</footer>
</body>
</html>
