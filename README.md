<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Photo Tools - Image Enhancer, PDF, Background Remover</title>
  <meta name="description" content="Free AI tools to upscale images, remove backgrounds, convert to PDF, enhance photos, and cartoonify images."/>
  <meta name="keywords" content="image upscaler, background remover, photo enhancer, image to PDF, cartoon image"/>
  <meta name="author" content="Your Name"/>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
    }

    .ad {
      text-align: center;
      background-color: #ddd;
      padding: 10px;
      font-size: 14px;
      font-weight: bold;
    }

    .ad-top {
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .main-layout {
      display: flex;
      flex-direction: row;
    }

    .ad-left, .ad-right {
      width: 120px;
      background: #eee;
      min-height: 100vh;
      padding: 10px;
    }

    .content {
      flex: 1;
      padding: 20px;
      text-align: center;
    }

    .tool-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .tool-card {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .tool-card:hover {
      transform: scale(1.02);
    }

    button {
      margin-top: 10px;
      padding: 8px 16px;
      background-color: #3b82f6;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <!-- Top Ad -->
  <div class="ad ad-top">
    <!-- Replace with your ad code -->
    Top Ad: <strong>Your Ad Unit ID</strong>
  </div>

  <div class="main-layout">

    <!-- Left Ad -->
    <div class="ad ad-left">
      Left Ad<br>
      <strong>Your Ad Unit ID</strong>
    </div>

    <!-- Main Content -->
    <main class="content">
      <h1>AI Photo Editing Tools</h1>
      <div class="tool-grid">
        <div class="tool-card">
          <h3>Image Upscaler</h3>
          <p>Increase image resolution with AI.</p>
          <button onclick="openTool('Image Upscaler')">Open</button>
        </div>
        <div class="tool-card">
          <h3>Background Remover</h3>
          <p>Remove or change image background.</p>
          <button onclick="openTool('Background Remover')">Open</button>
        </div>
        <div class="tool-card">
          <h3>Image to PDF</h3>
          <p>Convert images to a PDF file.</p>
          <button onclick="openTool('Image to PDF')">Open</button>
        </div>
        <div class="tool-card">
          <h3>Photo Enhancer</h3>
          <p>Sharpen blurry or low-quality images.</p>
          <button onclick="openTool('Photo Enhancer')">Open</button>
        </div>
        <div class="tool-card">
          <h3>Cartoonify Image</h3>
          <p>Convert photo to cartoon using AI.</p>
          <button onclick="openTool('Cartoonify Image')">Open</button>
        </div>
      </div>
    </main>

    <!-- Right Ad -->
    <div class="ad ad-right">
      Right Ad<br>
      <strong>Your Ad Unit ID</strong>
    </div>

  </div>

  <!-- JavaScript -->
  <script>
    function openTool(toolName) {
      alert(toolName + " is not yet connected. Backend coming soon!");
    }
  </script>

</body>
</html>
