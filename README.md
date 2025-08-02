<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Watong | Desarrollador Web</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', sans-serif;
      background-color: #0f172a;
      color: #f1f5f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
      min-height: 100vh;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #38bdf8;
    }

    p {
      font-size: 1.1rem;
      max-width: 600px;
      text-align: center;
      margin-bottom: 30px;
      color: #cbd5e1;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 30px;
    }

    .tag {
      background-color: #1e293b;
      border: 1px solid #334155;
      padding: 8px 14px;
      border-radius: 20px;
      font-size: 0.9rem;
      color: #f8fafc;
    }

    .links {
      display: flex;
      gap: 20px;
    }

    .links a {
      color: #38bdf8;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    .links a:hover {
      color: #0ea5e9;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1>Hola, soy Watong 👋</h1>
  <p>Desarrollador web apasionado por la tecnología, el diseño funcional y las soluciones creativas. Bienvenido a mi espacio en GitHub, donde comparto proyectos, ideas y experimentos de código.</p>

  <div class="tags">
    <span class="tag">HTML</span>
    <span class="tag">CSS</span>
    <span class="tag">JavaScript</span>
    <span class="tag">PHP</span>
    <span class="tag">MySQL</span>
    <span class="tag">React</span>
    <span class="tag">Node.js</span>
    <span class="tag">Git</span>
  </div>

  <div class="links">
    <a href="https://github.com/TU_USUARIO" target="_blank">🔗 GitHub</a>
    <a href="mailto:tuemail@ejemplo.com">📧 Contacto</a>
    <a href="https://tuportafolio.com" target="_blank">🌐 Portafolio</a>
  </div>
</body>
</html>
