
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Redireccionando...</title>
  <style>
    body {
      background-color: #0b0b0b;
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: sans-serif;
      flex-direction: column;
    }

    .loader {
      margin-top: 20px;
      width: 48px;
      height: 48px;
      border: 5px solid #fff;
      border-bottom-color: transparent;
      border-radius: 50%;
      display: inline-block;
      animation: rotate 1s linear infinite;
    }

    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <h2>Redireccionando a AstrosBet...</h2>
  <span class="loader"></span>

  <script>
    const encodedURL = "aHR0cHM6Ly9hc3Ryb3NiZXQudmlw";

    setTimeout(() => {
      const url = atob(encodedURL);
      window.location.href = url;
    }, 3000); // Espera 3 segundos antes de redirigir
  </script>
</body>
</html>
