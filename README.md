# Redirecci-n.apps<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Redirigiendo a la app...</title>
</head>
<body>
<script>
  var userAgent = navigator.userAgent || navigator.vendor || window.opera;

  if (/android/i.test(userAgent)) {
    window.location.href = "https://play.google.com/store/apps/details?id=fi.eleima.leimakortti&pcampaignid=web_share";
  } else if (/iPad|iPhone|iPod/.test(userAgent) && !window.MSStream) {
    window.location.href = "https://apps.apple.com/ni/app/winstamp-tarjeta-de-fidelidad/id1521626266";
  } else {
    window.location.href = "https://apps.apple.com/ni/app/winstamp-tarjeta-de-fidelidad/id1521626266";
  }
</script>
<p>Si no te redirige automáticamente, <a href="https://apps.apple.com/ni/app/winstamp-tarjeta-de-fidelidad/id1521626266">haz clic aquí</a>.</p>
</body>
</html>
