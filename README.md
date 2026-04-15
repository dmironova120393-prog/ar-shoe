# AR Shoe Try-On

WebAR shoe try-on using MediaPipe Pose + Three.js.  
Works in iPhone Safari — no app needed.

## Folder structure

```
your-repo/
├── index.html    ← the AR app
├── shoe.glb      ← YOUR shoe model (rename yours to shoe.glb)
└── README.md
```

## Deploy to GitHub Pages (free)

1. Create a new GitHub repository (public)
2. Upload `index.html`, `shoe.glb`, and `README.md`
3. Go to **Settings → Pages → Source: Deploy from branch → main → / (root)**
4. Save — your URL will be: `https://yourusername.github.io/your-repo-name/`

## iPhone usage

1. Open the GitHub Pages URL in **Safari** (not Chrome)
2. Tap **Camera** → allow camera access
3. Point at your feet from ~80 cm
4. Tap **Track** to start foot detection
5. Adjust **Scale** and **Height** sliders to fit your feet

## Tips for best tracking

- Good lighting, no strong shadows on feet
- Feet fully visible — don't crop ankles or toes
- Plain floor background works best
- Lower confidence sliders if tracking is unstable
