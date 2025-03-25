<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ログアウト中...</title>
    <script>
        setTimeout(function() {
            window.location.href = "https://photos.google.com/albums";
        }, 2000);  // 2秒後にリダイレクト
    </script>
</head>
<body>
    <p>Googleからログアウトしています...</p>
    <iframe src="https://accounts.google.com/Logout" style="display:none;"></iframe>
</body>
</html>