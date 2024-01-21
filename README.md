# 20240121_uchida_html

<!DOCTYPE html>
<html lang="ja">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>株式会社TECH</title>
</head>
<body>
	<header>
		<nav>
		<h1>株式会社TECH</h1>
		<ul>
			<li><a href="#">ホーム</a></li>
			<li><a href="#">企業情報</a></li>
			<li><a href="#">会社概要</a></li>
			<li><a href="#">よくある質問</a></li>
			<li><a href="#">お問い合わせ</a></li>
		</ul>
		</nav>
	</header>
	<main>
		<img src="html-test/mv.png" alt="">
		<p>最新のテクノロジーで<em>社会課題</em>を解決</p>
		<h2>会社概要</h2>
		<table>
			<tr>
				<th>会社名</th>
				<td>株式会社TECH</td>
			</tr>
			<tr>
				<th>代表者</th>
				<td>山田太郎</td>
			</tr>
			<tr>
				<th>所在地</th>
				<td>東京都渋谷区神宮前</td>
			</tr>
			<tr>
				<th>設立</th>
				<td>2019/07/17</td>
			</tr>
			<tr>
				<th>従業員数</th>
				<td>100人</td>
			</tr>
			<tr>
				<th>資本金</th>
				<td>1000万円</td>
			</tr>
		</table>
	</main>
	<footer>
		<h2>お問い合わせ</h2>
		<table>
		<form action="detail.html" method="post">
			<tr>
                <td><label>会社名<input type="text" /></label></td>
			</tr>
			<tr>
			    <td><label>お名前<input type="name" /></label></td>
			</tr>
			<tr>
			    <td><label>メールアドレス<input type="email" /></label></td>
			</tr>
			<tr>
				<td>
				<label>お問い合わせ内容
				<textarea name="textarea" cols="50" rows="5"></textarea></label>
				</td>
			</tr>
			<tr>
				<td><input type="submit" value="お申し込み"/></td>
			</tr>
		</form>
		</table>
		<small>&copy; 2020 TECH inc.</small>
	</footer>
</body>
</html>
