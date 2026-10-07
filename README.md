<!DOCTYPE html>
<html>
<head>
    <header>
  <div class="logo-container1000065100-removebg-preview.png"
    <!-- Links to your homepage and displays the logo -->
    <a href="index.html">
      <img src="1000065100-removebg-preview.png" alt="My site >:]" class="site-logo" width="200">
    </a>
  </div>
</header>

    <title>My Personal Web Article</title>

    <style>
        body {
            background-color: #00D7FF;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color: #Black;
            margin: 30px;
        }

        h1 {
            color: #004F5E;
            text-align: center;
        }

        h2 {
            color: 007085;
        }

        article {
            background-color: White;
            padding: 20px;
            border-radius: 10px;
        }

        img {
            width: 300px;
            height: auto;
        }

        a {
            color: Black;
        }

        button {
            background-color: Black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>

<body>

    <!-- Main Heading -->
    <h1>My Personal Web Article</h1>
<meta charset="UTF-8">
<style>
  .curved-gif {
    width: 300px;
    height: 200px;
    object-fit: cover;
  }
</style>
</head>

<br><br>
<body>

  <img src="ezgif-522282e841d91482.gif" alt="Animated GIF" class="curved-gif">

</body>
    <!-- Introduction -->

    <h2 style= "color=" blue>Introduction</h2>

<p class="intro-text">
Hello! My name is <b><u>Samantha Aguilar</u></b>. I am a Visual artist who enjoys
<i>drawing</i> and learning new things and other mixed media art related genres
<br>
I created this webpage to share about myself and to be my personal introduction.
</p>


    <!-- Article -->
    <article>

        <h2>About Me</h2>

        <p>
            I am a <strong>Multi-tasking</strong> person who enjoys
            <em>Researching about roblox and designing as my free time </em>. One of my favorite things to do is
            <b>take an existing character and redesigning them to my own vision using my creativity as well as designing my own world and writing a bit of lore in the process of the making.</b>.
        </p>

        <p>
            In my free time, I like to <i>research about old roblox games and watch horror series or ARGs from youtube.</i>.
            I also enjoy spending time with my family and my lovely partner Ivey♡ 
            <br><br>
            I hope to become <strong>A digital Artist, mainly to be an animator or storyboard artist for a game or indie company in canda</strong> in the futur, once i graduate from collage and save money to move. 
        </p>
        <br>
         <!-- My Fav Song and band -->
         <img src="Untitled716_20261007201950.png" alt="Spinning Gimmick" class="spinner">

    <p> My Fav Band/Song!</p>
         <audio controls loop>
  <source src="Waitress - Here Come The Cats.mp3" type="audio/mpeg">
</audio>
<br><br>
         
         
        <!-- Image -->
        <br>
        <h2>This is my Picture in cosplay!</h2>

        <img src="FB_IMG_1791149668436(1).jpg" alt="My Picture" width="100">

        <br><br>

        <!-- Website Link -->
        <p>
            This is my strawpage website!!! :
            <a href="https://introsheet.straw.page" target="_https://introsheet.straw.page">Strawpage</a>
        </p>

        <!-- Favorite Quote -->
        <h2>My Favorite Quote</h2>

        <blockquote>
            "Y'know not alot of people tends to apologies, your one of the people who genuinely shows they mean it."
        </blockquote>
    <p> —An ex-friend</p>
        <!-- Video -->
        <h2>My Video</h2>
    <p> Click me ⬇️</p>
       <a href="Tapee_1790930979789.mp4" target="_Tapee_1790930979789.mp4">
        <img src="received_2133416710933643.jpeg"
        " alt="Play Video" width="300">
        </a>

        <br><br>
        
</article>

    <br><br>
    
<!-- Button -->
<button onclick="alert('Thank you for visiting my webpage!')">
Thank You for Visiting!
</button>

<h5 style= "colour; Blue" Here is something to draw on while your bored ^^ </h5>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Interactive Drawing Pad</title>

  <style>
    /* ==============================
       DRAWING PAD
    ============================== */

    .drawing-gimmick {
      width: 100%;
      max-width: 600px;
      margin: 20px auto;
      padding: 15px;
      box-sizing: border-box;

      font-family: Arial, sans-serif;

      background: #f5f5f5;
      border: 1px solid #ddd;
      border-radius: 12px;

      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    }


    /* ==============================
       TOOLBAR
    ============================== */

    .toolbar {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 12px;

      padding: 12px;
      margin-bottom: 15px;

      background: white;
      border-radius: 10px;
      border: 1px solid #ddd;

      box-sizing: border-box;
    }


    .tool-item {
      display: flex;
      align-items: center;
      gap: 7px;

      font-size: 16px;
    }


    .tool-item label {
      font-weight: bold;
    }


    /* Color picker */

    #colorPicker {
      width: 45px;
      height: 35px;

      padding: 2px;

      border: 1px solid #aaa;
      border-radius: 5px;

      cursor: pointer;
    }


    /* Brush size */

    #brushSize {
      width: 130px;
      cursor: pointer;
    }


    #sizeValue {
      min-width: 35px;
    }


    /* Clear button */

    .clear-btn {
      padding: 9px 18px;

      background: #111;
      color: white;

      border: none;
      border-radius: 6px;

      font-size: 15px;
      font-weight: bold;

      cursor: pointer;
    }


    .clear-btn:hover {
      background: #333;
    }


    /* ==============================
       WHITE DRAWING AREA
    ============================== */

    .canvas-container {
      width: 100%;

      background: white;

      border: 3px solid #333;
      border-radius: 10px;

      overflow: hidden;

      /* Important for touch screens */
      touch-action: none;
    }


    #paintCanvas {
      display: block;

      width: 100%;
      height: 400px;

      background: white;

      cursor: crosshair;

      touch-action: none;
    }


    /* ==============================
       MOBILE
    ============================== */

    @media (max-width: 600px) {

      .drawing-gimmick {
        padding: 10px;
      }

      .toolbar {
        flex-direction: column;
        align-items: stretch;
      }

      .tool-item {
        justify-content: space-between;
      }

      #brushSize {
        flex: 1;
        width: auto;
      }

      .clear-btn {
        width: 100%;
        padding: 11px;
      }

      #paintCanvas {
        height: 350px;
      }
    }
  </style>
</head>


<body>

  <div class="drawing-gimmick">

    <!-- ==============================
         TOOLBAR
    ============================== -->

    <div class="toolbar">

      <!-- Color -->
      <div class="tool-item">
        <label for="colorPicker">Color:</label>

        <input
          type="color"
          id="colorPicker"
          value="#2563eb"
        >
      </div>


      <!-- Brush Size -->
      <div class="tool-item">

        <label for="brushSize">Size:</label>

        <input
          type="range"
          id="brushSize"
          min="1"
          max="30"
          value="5"
        >

        <span id="sizeValue">5px</span>

      </div>


      <!-- Clear -->
      <button
        type="button"
        class="clear-btn"
        id="clearBtn"
      >
        Clear
      </button>

    </div>


    <!-- ==============================
         WHITE DRAWING AREA
    ============================== -->

    <div class="canvas-container">

      <canvas id="paintCanvas"></canvas>

    </div>

  </div>


  <script>

    /* ==============================
       GET ELEMENTS
    ============================== */

    const canvas = document.getElementById("paintCanvas");
    const ctx = canvas.getContext("2d");

    const colorPicker =
      document.getElementById("colorPicker");

    const brushSize =
      document.getElementById("brushSize");

    const sizeValue =
      document.getElementById("sizeValue");

    const clearBtn =
      document.getElementById("clearBtn");


    let isDrawing = false;


    /* ==============================
       SET CANVAS SIZE
    ============================== */

    function resizeCanvas() {

      const rect = canvas.getBoundingClientRect();

      const dpr = window.devicePixelRatio || 1;

      canvas.width = rect.width * dpr;
      canvas.height = rect.height * dpr;

      ctx.scale(dpr, dpr);

      ctx.lineCap = "round";
      ctx.lineJoin = "round";
    }


    resizeCanvas();


    /* ==============================
       GET CORRECT DRAWING POSITION
    ============================== */

    function getPosition(event) {

      const rect = canvas.getBoundingClientRect();

      return {
        x: event.clientX - rect.left,
        y: event.clientY - rect.top
      };

    }


    /* ==============================
       START DRAWING
    ============================== */

    canvas.addEventListener("pointerdown", function(event) {

      event.preventDefault();

      isDrawing = true;

      canvas.setPointerCapture(event.pointerId);

      const position = getPosition(event);

      ctx.beginPath();

      ctx.moveTo(
        position.x,
        position.y
      );

    });


    /* ==============================
       DRAW
    ============================== */

    canvas.addEventListener("pointermove", function(event) {

      if (!isDrawing) return;

      event.preventDefault();

      const position = getPosition(event);

      ctx.lineWidth = Number(brushSize.value);

      ctx.strokeStyle = colorPicker.value;

      ctx.lineTo(
        position.x,
        position.y
      );

      ctx.stroke();

    });


    /* ==============================
       STOP DRAWING
    ============================== */

    function stopDrawing(event) {

      isDrawing = false;

      if (event.pointerId !== undefined) {

        try {
          canvas.releasePointerCapture(event.pointerId);
        } catch (error) {
          // Ignore if pointer capture was already released
        }

      }

      ctx.beginPath();
    }


    canvas.addEventListener(
      "pointerup",
      stopDrawing
    );

    canvas.addEventListener(
      "pointercancel",
      stopDrawing
    );


    /* ==============================
       BRUSH SIZE DISPLAY
    ============================== */

    brushSize.addEventListener("input", function() {

      sizeValue.textContent =
        brushSize.value + "px";

    });


    /* ==============================
       CLEAR CANVAS
    ============================== */

    clearBtn.addEventListener("click", function() {

      ctx.clearRect(
        0,
        0,
        canvas.width,
        canvas.height
      );

    });

  </script>
  
</body>
</html>

