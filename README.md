# I2C_LCD
<!DOCTYPE HTML>
<html>
<head>
<meta charset="utf-8">
<title>LCD Custom Character Generator</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="online character designer for Liquid Crystal Display (LCD) and create code for arduino.">
<meta name="keywords" content="lcd, lcd custom character, lcd character generator">
<link rel="stylesheet" href="css/prism.css" />
<link rel="stylesheet" href="css/style.css" />
</head>

<body>
<article class="content">
  <h1>LCD Custom Character Generator</h1>
  <h2>Support character lcd  and create code for Arduino.</h2>
  <div class="main-box">
    <div class="box-char-pic">
      <div class="box-char green">
        <div class="col">
          <div class="dot-px" data-x="0" data-y="0"></div>
          <div class="dot-px" data-x="0" data-y="1"></div>
          <div class="dot-px" data-x="0" data-y="2"></div>
          <div class="dot-px" data-x="0" data-y="3"></div>
          <div class="dot-px" data-x="0" data-y="4"></div>
        </div>
        <div class="col">
          <div class="dot-px" data-x="1" data-y="0"></div>
          <div class="dot-px" data-x="1" data-y="1"></div>
          <div class="dot-px" data-x="1" data-y="2"></div>
          <div class="dot-px" data-x="1" data-y="3"></div>
          <div class="dot-px" data-x="1" data-y="4"></div>
        </div>
        <div class="col">
          <div class="dot-px" data-x="2" data-y="0"></div>
          <div class="dot-px" data-x="2" data-y="1"></div>
          <div class="dot-px" data-x="2" data-y="2"></div>
          <div class="dot-px" data-x="2" data-y="3"></div>
          <div class="dot-px" data-x="2" data-y="4"></div>
        </div>
        <div class="col">
          <div class="dot-px" data-x="3" data-y="0"></div>
          <div class="dot-px" data-x="3" data-y="1"></div>
          <div class="dot-px" data-x="3" data-y="2"></div>
          <div class="dot-px" data-x="3" data-y="3"></div>
          <div class="dot-px" data-x="3" data-y="4"></div>
        </div>
        <div class="col">
          <div class="dot-px" data-x="4" data-y="0"></div>
          <div class="dot-px" data-x="4" data-y="1"></div>
          <div class="dot-px" data-x="4" data-y="2"></div>
          <div class="dot-px" data-x="4" data-y="3"></div>
          <div class="dot-px" data-x="4" data-y="4"></div>
        </div>
        <div class="col">
          <div class="dot-px" data-x="5" data-y="0"></div>
          <div class="dot-px" data-x="5" data-y="1"></div>
          <div class="dot-px" data-x="5" data-y="2"></div>
          <div class="dot-px" data-x="5" data-y="3"></div>
          <div class="dot-px" data-x="5" data-y="4"></div>
        </div>
        <div class="col">
          <div class="dot-px" data-x="6" data-y="0"></div>
          <div class="dot-px" data-x="6" data-y="1"></div>
          <div class="dot-px" data-x="6" data-y="2"></div>
          <div class="dot-px" data-x="6" data-y="3"></div>
          <div class="dot-px" data-x="6" data-y="4"></div>
        </div>
        <div class="col">
          <div class="dot-px" data-x="7" data-y="0"></div>
          <div class="dot-px" data-x="7" data-y="1"></div>
          <div class="dot-px" data-x="7" data-y="2"></div>
          <div class="dot-px" data-x="7" data-y="3"></div>
          <div class="dot-px" data-x="7" data-y="4"></div>
        </div>
      </div>
      <div class="btn-group">
        <button type="button" id="clear">Clear</button>
        &nbsp;&nbsp;&nbsp;&nbsp;
        <button type="button" id="invert">Invert</button>
      </div>
      <strong>Link</strong>
      <ul class="link-list">
        <li><a href="img/ArduinoUnoR3LCD.png" target="_blank">Arduino LCD Circuit</a></li>
        <li><a href="img/ArduinoUnoR3LCDI2C.png" target="_blank">Arduino LCD I2C Circuit</a></li>
        <li><a href="https://github.com/ROBOTICronics/I2C_LCD" target="_blank">Arduino LCD I2C library</a></li>
      </ul>
    </div>
    <div class="config">
      <form action="">
        <div class="inline">
          <strong>Color</strong>
          <label><input type="radio" id="color" name="color" value="green" checked> Green</label>
          <label><input type="radio" id="color" name="color" value="blue"> Blue</label>
        </div>
        <div class="inline">
          <strong>Microcontroller</strong>
          <label><input type="radio" id="mcu" name="mcu" value="Arduino" checked> Arduino</label>
        </div>
        <div class="inline">
          <strong>Interfacing</strong>
          <label><input type="radio" id="interfacing" name="interfacing" value="parallel" checked> Parallel</label>
          <label><input type="radio" id="interfacing" name="interfacing" value="i2c"> I2C</label>
        </div>
        <div class="inline">
          <strong>Data Type</strong>
          <label><input type="radio" id="datatype" name="datatype" value="bin" checked> Binary</label>
          <label><input type="radio" id="datatype" name="datatype" value="hex"> Hex</label>
        </div>
        <div class="inline">
          <strong>Code</strong>
        </div>
        <div class="inline">
          <pre><code class="language-cpp" id="code-box"></code></pre>
        </div>
      </form>
    </div>
  </div>
</article>
<footer>
  Open Source web tool By <a href="http://www.ioxhop.com/" target="_blank">IOXhop</a>
</footer>

<script src="js/jquery-1.11.3.min.js"></script>
<script src="js/prism.js"></script>
<script src="js/app.js"></script>

</body>
</html>
