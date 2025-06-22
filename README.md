<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Photo Tools - Free Image Enhancer, PDF Maker, Cartoonify</title>
  <meta name="description" content="Use free AI tools to upscale images, remove backgrounds, convert photos to PDF, enhance quality and cartoonify images."/>
  <meta name="keywords" content="image upscaler, background remover, photo enhancer, image to pdf, cartoonify, ai photo editor"/>
  <meta name="author" content="Your Name" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f0f0f0;
    }

    .ad {
      text-align: center;
      background: #ddd;
      padding: 10px;
      font-size: 14px;
    }

    .layout {
      display: flex;
    }

    .ad-left, .ad-right {
      width: 120px;
      background: #eee;
      padding: 10px;
      min-height: 100vh;
    }

    main {
      flex: 1;
      padding: 20px;
    }

    h1 {
      text-align: center;
    }

    .tools {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .tool-card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    .tool-card:hover {
      transform: scale(1.02);
      transition: 0.3s;
    }

    .tool-card input {
      margin-top: 10px;
    }

    .tool-card button {
      margin-top: 10px;
      padding: 8px 14px;
      background: #3b82f6;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      text-align: center;
      font-size: 13px;
      padding: 10px;
      background: #ddd;
    }
  </style>
</head>
<body>

  <!-- Top Ad -->
  <div class="ad">Top Ad Area — Ad Unit ID: <strong>top-banner-id</strong></div>

  <div class="layout">

    <!-- Left Ad -->
    <div class="ad ad-left">Left Ad — ID: <strong>left-sidebar-id</strong></div>

    <!-- Main Content -->
    <main>
      <h1>AI Photo Tools</h1>
      <div class="tools">

        <!-- Image Upscaler -->
        <div class="tool-card">
          <h3>Image Upscaler</h3>
          <input type="file" accept="image/*" />
          <button onclick="showMessage('Image Upscaler')">Start</button>
        </div>

        <!-- Background Remover -->
        <div class="tool-card">
          <h3>Background Remover</h3>
          <input type="file" accept="image/*" />
          <button onclick="showMessage('Background Remover')">Start</button>
        </div>

        <!-- Image to PDF -->
        <div class="tool-card">
          <h3>Image to PDF</h3>
          <input type="file" accept="image/*" multiple />
          <button onclick="showMessage('Image to PDF')">Convert</button>
        </div>

        <!-- Photo Enhancer -->
        <div class="tool-card">
          <h3>Photo Enhancer</h3>
          <input type="file" accept="image/*" />
          <button onclick="showMessage('Photo Enhancer')">Enhance</button>
        </div>

        <!-- Cartoonify Image -->
        <div class="tool-card">
          <h3>Cartoonify Image</h3>
          <input type="file" accept="image/*" />
          <button onclick="showMessage('Cartoonify Image')">Cartoonify</button>
        </div>

      </div>
    </main>

    <!-- Right Ad -->
    <div class="ad ad-right">Right Ad — ID: <strong>right-sidebar-id</strong></div>
  </div>

  <footer>© 2025 AI Photo Tools. All rights reserved.</footer>

  <script>
    function showMessage(toolName) {
      alert(toolName + " is not connected to backend yet. Please add API or logic.");
    }
  </script>
</body>
</html>
