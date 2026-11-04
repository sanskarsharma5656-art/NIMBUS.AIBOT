[README.txt](https://github.com/user-attachments/files/34355255/README.txt)
NIMBUS AI - FREE AI CHATBOT

This is a static website with a real local AI model powered by WebLLM. It does not need an API key or paid hosting. It is NOT powered by OpenAI or Gemini.

TO PUBLISH FREE:
1. Go to github.com and create a PUBLIC repository called my-ai-chatbot (or any name).
2. Upload the file index.html from this ZIP to the root of your repository. Commit changes.
3. Go to Settings > Pages > Build and deployment. Select "Deploy from a branch", branch "main", folder "/ (root)", then Save.
4. Open https://YOURUSERNAME.github.io/my-ai-chatbot/ (replace YOURUSERNAME and repo name).
5. Click "Start AI" on a recent WebGPU-compatible Chrome or Edge browser. The first run downloads the selected model, which can be large and may take time.

TO APPEAR ON GOOGLE SEARCH:
1. Visit https://search.google.com/search-console/about
2. Add a URL-prefix property using your full site URL.
3. Use the HTML tag verification method. Edit index.html, paste the Google-provided <meta ...> tag inside the <head> section, and commit the change. After the update publishes, click Verify.
4. Inspect your full site URL and click "Request indexing" if available. Google does not guarantee indexing or ranking.

OPTIONAL GOOGLE SITES FRONT PAGE:
You can also publish a Google Sites page that links to your GitHub Pages AI chatbot.

NOTES:
- Works only where WebGPU is available; many phones and older devices won't support it.
- The better 1.7B model needs much more RAM/GPU capacity than Lite.
- AI answers are from a SMALL offline-inference model, not ChatGPT-quality.
- The first load downloads model files over the internet, then the model runs locally in the browser.
- The free hosting repository must be public; never put secrets, passwords or API keys in it.
