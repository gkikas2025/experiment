<!DOCTYPE html>
<html lang="el">
<head>
  <meta charset="UTF-8">
  <title>AI Movie Recommender – Scenario 1</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* Βασικό στυλ */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #f0f4f8, #e6edf2);
      color: #333;
    }

    /* Container */
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 40px 20px;
    }

    /* Τίτλος */
    h1 {
      text-align: center;
      color: #2c3e50;
      margin-bottom: 20px;
      font-size: 2.5rem;
    }

    /* Κείμενο οδηγίες */
    p {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: 20px;
      text-align: center;
    }

    /* Chatbot container */
    #vf-chat {
      width: 100%;
      max-width: 450px;
      height: 550px;
      margin: 30px auto;
      border: 2px solid #3498db;
      border-radius: 12px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      background-color: #fff;
    }

    /* Footer / επιπλέον οδηγίες */
    .footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.95rem;
      color: #555;
    }

    /* Responsive */
    @media (max-width: 500px) {
      h1 { font-size: 2rem; }
      #vf-chat { height: 500px; }
      p { font-size: 1rem; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>AI Movie Recommender</h1>
    <p>Καλωσόρισες στο πρώτο σενάριο του πειράματος! 🎬</p>
    <p>Διάλεξε τις προτιμήσεις σου και άφησε τον AI agent να σου προτείνει τις καλύτερες ταινίες για εσένα.</p>

    <!-- Chatbot container -->
    <div id="vf-chat"></div>

    <div class="footer">
      Ακολούθησε τις οδηγίες του chatbot για να ολοκληρώσεις τη διαδικασία. Ευχαριστούμε για τη συμμετοχή σου! ❤️
    </div>
  </div>

  <!-- Voiceflow Web Chat Widget -->
  <script>
    (function(d, t) {
      var v = d.createElement(t), s = d.getElementsByTagName(t)[0];
      v.onload = function() {
        window.voiceflow.chat.load({
          verify: { projectID: '67d13d93fe835fadf86ddc3f' },
          url: 'https://general-runtime.voiceflow.com',
          versionID: 'development',
          render: {
            mode: 'embedded',
            target: document.getElementById('vf-chat')
          },
          autostart: true
        });
      };
      v.src = "https://cdn.voiceflow.com/widget/bundle.mjs";
      v.type = "module";
      s.parentNode.insertBefore(v, s);
    })(document, 'script');
  </script>
</body>
</html>
