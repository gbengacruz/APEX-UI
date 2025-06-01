<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Oracle APEX UI Design - GitHub Repository</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 2rem; line-height: 1.6; background: #f9f9f9; color: #333; }
    h1, h2 { color: #004080; }
    code { background: #eee; padding: 2px 4px; border-radius: 3px; }
    .screenshot-container { display: flex; gap: 1rem; margin-top: 1rem; }
    .screenshot-container img { width: 30%; border: 1px solid #ccc; border-radius: 6px; }
    .note { background: #e8f4ff; padding: 1rem; border-left: 5px solid #0073e6; margin-top: 1rem; border-radius: 4px; }
  </style>
</head>
<body>
  <h1>Oracle APEX UI Design</h1>
  <p>This repository provides a pre-built Oracle APEX application with customized UI themes and a user-friendly interface. The application is ideal for UI design learning, prototyping, or extension into production use.</p>

  <h2>📥 Importing the APEX App</h2>
  <ol>
    <li>Login to your Oracle APEX workspace.</li>
    <li>Navigate to <strong>App Builder</strong>.</li>
    <li>Click <strong>Import</strong>.</li>
    <li>Upload the file <code>f144.sql</code> provided in this repository.</li>
    <li>Follow the prompts to complete the installation.</li>
    <li>Once imported, open the application to begin customization or exploration.</li>
  </ol>

  <h2>🎨 Changing the Theme Style</h2>
  <p>To change the theme style dynamically within the app:</p>
  <ol>
    <li>Run the application from the App Builder.</li>
    <li>Navigate to the <strong>Theme Style Selection</strong> component (usually in the settings or navbar).</li>
    <li>Click on the style selector and choose from available styles (e.g., Light, Dark, Custom).</li>
    <li>The UI will update to reflect your selected theme immediately.</li>
  </ol>

  <div class="note">
    <strong>Tip:</strong> Theme styles are controlled via <em>User Interface Attributes</em> in Shared Components. You can also modify or create your own styles there.
  </div>

  <h2>🖼️ Sample Themes</h2>
  <p>Here are sample screenshots of different UI theme styles available in the application:</p>
  <div class="screenshot-container">
    <img src="1.png" alt="Theme Style 1">
    <img src="2.png" alt="Theme Style 2">
    <img src="3.png" alt="Theme Style 3">
  </div>

  <hr>
  <footer>
    <p>For more details, visit the official <a href="https://apex.oracle.com/" target="_blank">Oracle APEX site</a>.</p>
  </footer>
</body>
</html>
