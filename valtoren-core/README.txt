Valtoren Core website - Vercel deployment
==========================================

Files
  index.html   The complete website (all images and code are inside this one file)
  favicon.svg  Browser tab icon (VC logo)
  vercel.json  Vercel settings
  robots.txt, sitemap.xml  For Google search

Deploy (no coding needed)
  1. Go to https://vercel.com and log in (or sign up free).
  2. Click "Add New..." > "Project".
  3. Drag this whole folder (valtoren-core) onto the upload area,
     or push it to a GitHub repo and click "Import".
  4. Framework Preset: "Other". Leave Build Command and Output Directory empty.
  5. Click "Deploy". You get a live link like valtoren-core.vercel.app

Deploy with the command line (optional)
  npm i -g vercel
  cd valtoren-core
  vercel --prod

Connect www.valtorencore.com
  Project > Settings > Domains > add www.valtorencore.com,
  then add the DNS record Vercel shows you at your domain provider.

Contact details used on the site
  WhatsApp: +92 331 3832401
  Phone:    +92 81 2829900
  Email:    contact@valtorencore.com
  To change them, search index.html for 923313832401 and +92812829900.
