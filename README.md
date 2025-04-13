
:wave: Hi! My name is Michelle. I am an aspiring computer science engineer. 

<div align="center">
  <style>
    .cube-container {
      width: 150px;
      height: 150px;
      perspective: 1000px;
      margin: 40px auto;
    }

    .cube {
      width: 100%;
      height: 100%;
      position: relative;
      transform-style: preserve-3d;
      transform: translateZ(-75px);
      animation: rotate-cube 15s infinite linear;
    }

    .cube-face {
      position: absolute;
      width: 150px;
      height: 150px;
      border: 1px solid #555;
      background-color: rgba(60, 60, 60, 0.8);
      color: #fff;
      font-size: 16px;
      font-weight: bold;
      display: flex;
      justify-content: center;
      align-items: center;
      backface-visibility: hidden;
    }

    .front  { transform: rotateY(  0deg) translateZ(75px); background-color: rgba(0, 120, 215, 0.8); }
    .back   { transform: rotateY(180deg) translateZ(75px); background-color: rgba(215, 0, 0, 0.8); }
    .right  { transform: rotateY( 90deg) translateZ(75px); background-color: rgba(0, 215, 0, 0.8); }
    .left   { transform: rotateY(-90deg) translateZ(75px); background-color: rgba(215, 215, 0, 0.8); }
    .top    { transform: rotateX( 90deg) translateZ(75px); background-color: rgba(215, 0, 215, 0.8); }
    .bottom { transform: rotateX(-90deg) translateZ(75px); background-color: rgba(0, 215, 215, 0.8); }

    @keyframes rotate-cube {
      from { transform: rotateX(0deg) rotateY(0deg); }
      to   { transform: rotateX(360deg) rotateY(360deg); }
    }
  </style>

  <div class="cube-container">
    <div class="cube">
      <div class="cube-face front">Front</div>
      <div class="cube-face back">Back</div>
      <div class="cube-face right">Right</div>
      <div class="cube-face left">Left</div>
      <div class="cube-face top">Top</div>
      <div class="cube-face bottom">Bottom</div>
    </div>
  </div>

</div>
<div id="header" align="center">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExendkd2syMjZsdmdxNDAzcnF0NzV3MGl2YndiOWljYWRiZnZ5M2VqZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/A4wSE2GQGTpfi/giphy.gif" width="1500" height="300"/>
</div
<br>
<hr>

<b>🪐All About Michelle🪐</b>
<br>
- :rocket: I am currently enrolled at IES College of Engineering pursuing my degree in Computer Science Engineering.
- :dizzy: I like intense conversations and brightly coloured beverages :tropical_drink:.
- :tv: Currently binging Mr Robot and wondering how to center a div. (<i>I also have an excellent sense of humour</i>)
- :writing_hand: Always creating.
- :brain: I love learning.
- Click to follow my LinkedIn.<div id="badges" align="50%">
  <a href=https://www.linkedin.com/in/michelle-a-956893253/>
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
