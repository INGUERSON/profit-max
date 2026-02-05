# profit-max
aplicativo para personais e alunos

<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" />
    <title>FitPro Max</title>
    <meta name="description" content="Acompanhamento de treino e evolução corporal." />
    <link rel="manifest" href="/manifest.json" />
    
    <!-- PWA Meta Tags para iOS (iPhone/iPad) -->
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
    <meta name="apple-mobile-web-app-title" content="FitPro Max" />
    <link rel="apple-touch-icon" href="https://picsum.photos/192/192" />
    <link rel="apple-touch-startup-image" href="https://picsum.photos/512/512" />

    <!-- PWA Meta Tags para Android e outros -->
    <meta name="mobile-web-app-capable" content="yes" />
    <meta name="theme-color" content="#020617" />
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      tailwind.config = {
        darkMode: 'class',
        theme: {
          extend: {
            colors: {
              brand: {
                neon: '#a3e635', // Lime 400
                dark: '#020617', // Slate 950
                card: '#0f172a', // Slate 900
                border: '#1e293b' // Slate 800
              }
            }
          }
        }
      }
    </script>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');
      body {
        font-family: 'Inter', sans-serif;
        background-color: #020617;
        color: white;
        overscroll-behavior-y: contain;
        /* Padding extra para a barra de status do iOS no modo standalone */
        padding-top: env(safe-area-inset-top);
      }
      
      ::-webkit-scrollbar { display: none; }
      
      .safe-area-bottom {
        padding-bottom: env(safe-area-inset-bottom);
      }
    </style>
  <script type="importmap">
{
  "imports": {
    "react/": "https://esm.sh/react@^19.2.4/",
    "react": "https://esm.sh/react@^19.2.4",
    "react-dom/": "https://esm.sh/react-dom@^19.2.4/",
    "lucide-react": "https://esm.sh/lucide-react@^0.563.0",
    "recharts": "https://esm.sh/recharts@^3.7.0",
    "@google/genai": "https://esm.sh/@google/genai@^1.40.0"
  }
}
</script>
</head>
  <body>
    <div id="root"></div>
  </body>
</html>
