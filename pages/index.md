---
layout: null
permalink: /
---

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Redirecting…</title>

  <!-- Мгновенный редирект -->
  <meta http-equiv="refresh" content="0; url={{ '/about' | relative_url }}">

  <!-- Канонический URL -->
  <link rel="canonical" href="{{ '/about' | relative_url }}">

  <script>
    // JS-редирект на случай, если meta не сработает
    window.location.replace("{{ '/about' | relative_url }}");
  </script>
</head>
<body>
  <p>If you are not redirected automatically,
     <a href="{{ '/about' | relative_url }}">click here</a>.
  </p>
</body>
</html>