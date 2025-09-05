<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Shuvashish | Profile</title>
<style>
  :root{
    --fg:#fff; --accent:#58a6ff;
    --icon:clamp(56px,8vw,92px);
  }
  body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,sans-serif;background:#0d1117;color:var(--fg)}
  .hero{position:relative;min-height:100vh;display:flex;align-items:center;justify-content:center;text-align:center;padding:clamp(16px,4vw,40px)}
  .hero video{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;z-index:-1;filter:brightness(.35)}
  .card{width:min(100%,1000px);background:rgba(13,17,23,.55);border:1px solid rgba(255,255,255,.12);backdrop-filter:blur(8px);border-radius:16px;padding:clamp(16px,4vw,40px);box-shadow:0 10px 30px rgba(0,0,0,.3)}
  h1{margin:0 0 6px;font-size:clamp(26px,5vw,42px)}
  .lead{margin:6px 0 18px;font-size:clamp(14px,3vw,18px)}
  .links{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin:10px 0 18px}
  .pill{display:inline-flex;gap:8px;align-items:center;padding:8px 12px;border:1px solid rgba(255,255,255,.12);border-radius:999px;background:rgba(255,255,255,.06)}
  a{color:var(--accent);text-decoration:none}
  a:hover{text-decoration:underline}
  .icons{display:flex;flex-wrap:wrap;gap:14px;justify-content:center;margin:18px 0 6px}
  .icons img{width:var(--icon);height:var(--icon)}
  .fb{display:flex;gap:14px;justify-content:center;align-items:center;flex-wrap:wrap;margin-top:18px}
  .fb img{width:120px;border-radius:50%;border:1px solid rgba(255,255,255,.12)}
  @media (prefers-reduced-motion: reduce){ .hero video{display:none} }
</style>
</head>
<body>
  <section class="hero">
    <!-- ✅ Whole-div video background -->
    <video autoplay muted loop playsinline preload="auto" poster="">
      <source src="https://res.cloudinary.com/dl4lfh8em/video/upload/v1757064721/shuvasis_nlh2io.mp4" type="video/mp4">
    </video>

    <div class="card">
      <!-- Typing headline -->
      <p style="margin:0 0 8px">
        <a href="https://git.io/typing-svg">
          <img
            src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=2200&pause=500&color=FFFFFF&center=true&vCenter=true&repeat=true&width=900&background=00000000&lines=Hi%20%F0%9F%91%8B;I'm%20Shuvashish%20Sharma;Undergraduate%20Physics%20Student;Computational%20Physics%20Enthusiast;Data%20Science%20%26%20Machine%20Learning"
            alt="Typing"
          />
        </a>
      </p>
      <p class="lead">Dhaka, Bangladesh • I explain physics simply and love data-driven research.</p>

      <div class="links">
        <span class="pill">Latest push <img alt="last commit" src="https://img.shields.io/github/last-commit/Shuvashish33-lab/Shuvashish33-lab?logo=github&label=&color=white&labelColor=000000&logoColor=white"></span>
        <a class="pill" href="https://github.com/Shuvashish33-lab" target="_blank" rel="noopener">GitHub</a>
        <a class="pill" href="https://www.linkedin.com/in/shuvashish-sharma-a95b27199" target="_blank" rel="noopener">LinkedIn</a>
        <a class="pill" href="mailto:shuvashish33@gmail.com">Email</a>
      </div>

      <!-- Big skills (Devicon) -->
      <div class="icons" aria-label="Skills">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" alt="scikit-learn"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" alt="MATLAB"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/latex/latex-original.svg" alt="LaTeX"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow"/>
      </div>

      <!-- FB widget (image + text) -->
      <div class="fb">
        <a href="https://facebook.com/shodip.sharma" target="_blank" rel="noopener">
          <img src="https://graph.facebook.com/shodip.sharma/picture?type=large" alt="Facebook Photo"/>
        </a>
        <div style="text-align:left;max-width:520px">
          <strong>Name:</strong> Shuvashish Sharma<br/>
          <strong>Profile:</strong> <a href="https://facebook.com/shodip.sharma">facebook.com/shodip.sharma</a><br/>
          <strong>Open to:</strong> Research collabs & open-source work
        </div>
      </div>
    </div>
  </section>
</body>
</html>
