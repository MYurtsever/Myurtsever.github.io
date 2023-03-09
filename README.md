<!DOCTYPE html>
<html>
<head>
	<title>Benim Web Sitem</title>
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="#anasayfa">Anasayfa</a></li>
				<li><a href="#hakkimda">Hakkımda</a></li>
				<li><a href="#iletisim">İletişim</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<section id="anasayfa">
			<h1>Hoş Geldiniz!</h1>
			<p>Benim adım Mehmet, bu benim web sitem. Burada kendim hakkında bilgi veriyorum ve bazı projelerimi paylaşıyorum. Umarım burada ihtiyacınız olan her şeyi bulabilirsiniz!</p>
		</section>

		<section id="hakkimda">
			<h2>Hakkımda</h2>
			<p>Ben bir yazılım geliştiricisiyim ve çeşitli programlama dilleriyle çalışıyorum. En sevdiğim dil Python, ancak son zamanlarda JavaScript'e de ilgi duymaya başladım.</p>
			<p>Bunun dışında, boş zamanlarımda kitap okumayı, yürüyüş yapmayı ve seyahat etmeyi severim.</p>
		</section>

		<section id="iletisim">
			<h2>İletişim</h2>
			<p>Eğer benimle iletişime geçmek isterseniz, aşağıdaki formu doldurabilirsiniz.</p>
			<form>
				<label for="ad">Adınız:</label>
				<input type="text" id="ad" name="ad"><br>

				<label for="soyad">Soyadınız:</label>
				<input type="text" id="soyad" name="soyad"><br>

				<label for="email">E-posta:</label>
				<input type="email" id="email" name="email"><br>

				<label for="mesaj">Mesajınız:</label><br>
				<textarea id="mesaj" name="mesaj" rows="4" cols="50"></textarea><br>

				<input type="submit" value="Gönder">
			</form>
		</section>
	</main>

	<footer>
		<p>© 2023 Mehmet yurtsever</p>
	</footer>
</body>
</html>
