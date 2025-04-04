# RedRedRyan's GitHub Profile

<div align="center">
  <h1>RedRedRyan</h1>
  <p>ryankipkorir@gmail.com</p>
</div>

<style>
  body {
    margin: 0;
    padding: 0;
    height: 100vh;
    overflow: hidden;
    background: #000;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100px;
    background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MTIgNTEyIj48cGF0aCBmaWxsPSIjRkYwMDAwIiBkPSJNNTEyIDUxMlYwaC01MTJ2NTEyaDUxMnoiLz48L3N2Zz4=') repeat-x;
    background-size: 1000px 100px;
    animation: wave 7s linear infinite;
    z-index: -1;
  }

  @keyframes wave {
    0% { background-position: 0 0; }
    100% { background-position: 1000px 0; }
  }

  .content {
    position: relative;
    z-index: 1;
    color: white;
    text-align: center;
    padding: 20px;
    background: rgba(0, 0, 0, 0.5);
    border-radius: 10px;
  }
</style>

<div class="wave"></div>
<div class="content">
  <h1>RedRedRyan</h1>
  <p>Developer | Creator | Explorer</p>
  <p>Check out my repositories for more!</p>
</div>
