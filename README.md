<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Data Cleaning Summary</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      padding: 40px;
    }
    h1 {
      color: #0066cc;
    }
    .section {
      background: #ffffff;
      padding: 20px;
      margin-top: 20px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    ul {
      line-height: 1.6;
    }
    code {
      background: #eee;
      padding: 2px 6px;
      border-radius: 4px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <h1>📊 Data Cleaning Report</h1>

  <div class="section">
    <h2>🧹 Cleaning Performed</h2>
    <ul>
      <li>Removed 54 duplicate rows.</li>
      <li>Standardized <code>Date</code> format to <code>dd-mm-yyyy</code>.</li>
      <li>Capitalized all entries in the <code>Name</code> column.</li>
    </ul>
  </div>

  <div class="section">
    <h2>📁 Files Included</h2>
    <ul>
      <li><code>cleaned_data.xlsx</code> – Cleaned and formatted dataset</li>
      <li><code>README.html</code> – This report file</li>
    </ul>
  </div>

</body>
</html>
