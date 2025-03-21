# mironnik.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Redirect Button</title>
  <style>
    body {
      display: flex;
      height: 100vh;
      justify-content: center;
      align-items: center;
      background-color: #f0f0f0;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      border-radius: 8px;
      border: none;
      background-color: #4CAF50;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <button onclick="window.location.href='https://propush.nmironov.ru/push.html'">Go to Push Page</button>

</body>
</html>

<!-- <iframe src="https://propush.nmironov.ru/notix.html"/> -->
<!-- <head>
<script>
    var s = document.createElement('script');
    s.src='//propush.nmironov.ru/micro.tag.min.js?z=7074860'+'&sw=/sw-check-permissions-cecd2.js';
    s.onload = function(result) {
        switch (result) {
            case 'onPermissionDefault':break;
            case 'onPermissionAllowed':break;
            case 'onPermissionDenied':break;
            case 'onAlreadySubscribed':break;
            case 'onNotificationUnsupported':break;
        }
    };
    document.head.appendChild(s);
</script>
</head> -->
