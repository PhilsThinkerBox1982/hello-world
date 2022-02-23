

<!doctype html>
<?php
$cookie_name = "user";
$cookie_value = "blackoctopuscartoons";
setcookie($cookie_name, $cookie_value, time() + (86400 * 30), "/"); // 86400 = 1 day
?>
<html lang="en">

  <head>

    <meta charset="utf-8">

    <title></title>

    <link rel="stylesheet" href="../webgl.css" type="text/css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
<style>

.error {color: #FF0000;}

  canvas {

	border: 2px solid black;

	background-color: blue;

}

video {

	display: none;

}

.feed-links {display:none !important;}
  
 #top {
    border: 1px solid blue;
    height: 500px;
}
   

#bottom {
    border: 1px solid red;
} 
  
  
</style>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/gl-matrix/2.8.1/gl-matrix-min.js"

      integrity="sha512-zhHQR0/H5SEBL3Wn6yYSaTTZej12z0hVZKOv3TwCUXT1z5qeqGcXJLLrbERYRScEDDpYIJhPC1fk31gqR783iQ=="

      crossorigin="anonymous" defer>

    </script>

    <script src="webgl-demo.js" defer>

    

    </script>
    
    <!-- Global site tag (gtag.js) - Google Analytics -->

<script async src="https://www.googletagmanager.com/gtag/js?id=G-H3KRV7YLRV"></script>

<script>

  window.dataLayer = window.dataLayer || [];

  function gtag(){dataLayer.push(arguments);}

  gtag('js', new Date());

  gtag('config', 'G-H3KRV7YLRV');

</script>
</head>

  
  
  
  




<body>

  <script>
  document.getElementById( 'bottom' ).scrollIntoView();




function top() {
    document.getElementById( 'top' ).scrollIntoView();    
};

function bottom() {
    document.getElementById( 'bottom' ).scrollIntoView();
    window.setTimeout( function () { top(); }, 2000 );
};

bottom();
  </script>
<div id="top" style="padding: 15px; background-color: black";><p style="font-family: 'Press Start 2P'">Send HTML files to: phillipmacias@blackoctopuscartoons.com
  <br>
  <br>
 github.com/PhilsThinkerBox1982
  </p></div>
<div id="top" style="padding: 10px"><p style="text-align: center; font-size: 14px; font-family: 'Press Start 2P'">
  <br>
  <br>
  <br>
  <br>
  ` 1 2 3 4 5 6 7 8 9 0 - = ~ ! @ # $ % ^ & * ( ) _ + backspace
  <br>
  <br>
  <br>
  <br>
  t a b q w e r t y u i o p [ ] \ Q W E R T Y U I O P { } |
  <br>
  <br>
  <br>
  <br>
  s h i f t z x c v b n m , . / s h i f t Z X C V B N M < > ?
  <br>
  <br>
  <br>
  <br>
  ctrl alt spacebar alt ctrl left down up right
  </p>
  
  
  
  <br>
  
  </div>


  
  
  
  
  
  
  
  
  
  <br>
  
  
  
  
 <canvas id="cookie" width="100" height="100" style="background-color:chocolate; border:1px solid #000000;">   
  </canvas> 
  <br />
<?php
if(!isset($_COOKIE[$cookie_name])) {
     echo "Cookie named '" . $cookie_name . "' is not set!";
} else {
     echo "Cookie '" . $cookie_name . "' is set!<br>";
     echo "Value is: " . $_COOKIE[$cookie_name];
}
?>
  

 

  

  <script>
  var c = document.getElementById("cookie");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.rect(10, 10, 10, 10);
ctx.stroke();
    ctx.fillStyle = "brown";

ctx.fill();
    


ctx.beginPath();

ctx.rect(10, 50, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
    

ctx.beginPath();

ctx.rect(10, 75, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
 


ctx.beginPath();

ctx.rect(50, 30, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
    
    ctx.beginPath();

ctx.rect(75, 75, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
    
    
     ctx.beginPath();

ctx.rect(75, 10, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
    
    
    
</script>
  
  
  
  
  
  
  <canvas id="rabbit" width="100" height="100" style="background-color:black; border:1px solid #000000;">   
  </canvas>
  

  <script>
  var c = document.getElementById("rabbit");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.rect(20, 50, 50, 50);
ctx.stroke();
    ctx.fillStyle = "white";

ctx.fill();
    
var d = document.getElementById("rabbit");

var ctx = c.getContext("2d");

ctx.beginPath();

ctx.rect(10, 75, 25, 25);

ctx.stroke();

    ctx.fillStyle = "white";

ctx.fill();
    
 var e = document.getElementById("rabbit");

var ctx = c.getContext("2d");

ctx.beginPath();

ctx.rect(10, 30, 50, 10);

ctx.stroke();

    ctx.fillStyle = "white";

ctx.fill();
 
var f = document.getElementById("rabbit");

var ctx = c.getContext("2d");

ctx.beginPath();

ctx.rect(50, 30, 35, 35);

ctx.stroke();

    ctx.fillStyle = "white";

ctx.fill();
    
    
</script>
  
  <br>
  
  
  
  
  
  <?php
  echo $_SERVER['PHP_SELF'];
echo "<br>";
echo $_SERVER['SERVER_NAME'];
echo "<br>";
echo $_SERVER['HTTP_HOST'];
echo "<br>";
echo $_SERVER['HTTP_REFERER'];
echo "<br>";
echo $_SERVER['HTTP_USER_AGENT'];
echo "<br>";
echo $_SERVER['SCRIPT_NAME'];
?>
  
  
  <br />
  
  
  
  
  
  
  <?php
// router.php
if (preg_match('/\.(?:png|jpg|jpeg|gif)$/', $_SERVER["REQUEST_URI"])) {
    return false;    // serve the requested resource as-is.
} else { 
    echo "<p>Welcome to PHP</p>";
}
?>
  
  
  
  
<?php
// define variables and set to empty values
$nameErr = $emailErr = $genderErr = $websiteErr = "";
$name = $email = $gender = $comment = $website = "";

if ($_SERVER["REQUEST_METHOD"] == "POST") {
  if (empty($_POST["name"])) {
    $nameErr = "Name is required";
  } else {
    $name = test_input($_POST["name"]);
    // check if name only contains letters and whitespace
    if (!preg_match("/^[a-zA-Z-' ]*$/",$name)) {
      $nameErr = "Only letters and white space allowed";
    }
  }
  
  if (empty($_POST["email"])) {
    $emailErr = "Email is required";
  } else {
    $email = test_input($_POST["email"]);
    // check if e-mail address is well-formed
    if (!filter_var($email, FILTER_VALIDATE_EMAIL)) {
      $emailErr = "Invalid email format";
    }
  }
    
  if (empty($_POST["website"])) {
    $website = "";
  } else {
    $website = test_input($_POST["website"]);
    // check if URL address syntax is valid
    if (!preg_match("/\b(?:(?:https?|ftp):\/\/|www\.)[-a-z0-9+&@#\/%?=~_|!:,.;]*[-a-z0-9+&@#\/%=~_|]/i",$website)) {
      $websiteErr = "Invalid URL";
    }    
  }

  if (empty($_POST["comment"])) {
    $comment = "";
  } else {
    $comment = test_input($_POST["comment"]);
  }

  if (empty($_POST["gender"])) {
    $genderErr = "Gender is required";
  } else {
    $gender = test_input($_POST["gender"]);
  }
}

function test_input($data) {
  $data = trim($data);
  $data = stripslashes($data);
  $data = htmlspecialchars($data);
  return $data;
}
?>

<h2 style="font-family: 'Press Start 2P'">PHP Form Validation Example</h2>
<p><span class="error" style="color: white;">* required field</span></p>
<form method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>">  
  Name: <input type="text" name="name">
  <span class="error" style="color: white;">* <?php echo $nameErr;?></span>
  
  
  
  
  <canvas id="cookie1" width="100" height="100" style="background-color:chocolate; border:1px solid #000000;">   
  </canvas>

 

  

  <script>
  var c = document.getElementById("cookie1");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.rect(25, 25, 10, 10);
ctx.stroke();
    ctx.fillStyle = "brown";

ctx.fill();
    
    ctx.beginPath();
ctx.rect(10, 10, 10, 10);
ctx.stroke();
    ctx.fillStyle = "brown";

ctx.fill();
    

    


ctx.beginPath();

ctx.rect(75, 50, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
    

ctx.beginPath();

ctx.rect(10, 75, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
 


ctx.beginPath();

ctx.rect(50, 30, 10, 10);

ctx.stroke();

    ctx.fillStyle = "brown";

ctx.fill();
    
    ctx.beginPath();

ctx.rect(75, 25, 10, 10);

ctx.stroke();

    ctx.fillStyle = "";

ctx.fill();
    
</script>
  
  
  
  
  
  
  
  <br />
  <!--
  E-mail: <input type="text" name="email">
  <span class="error">* <?php echo $emailErr;?></span>
-->
  
  <!--
  Website: <input type="text" name="website">
  <span class="error"><?php echo $websiteErr;?></span>
-->
 
  Comment: <textarea name="comment" rows="5" cols="40" ></textarea>
  <br>
  <!--
  Gender:
  <input type="radio" name="gender" value="female">Female
  <input type="radio" name="gender" value="male">Male
  <input type="radio" name="gender" value="other">Other
  <span class="error">* <?php echo $genderErr;?></span>
-->
  
  <input type="submit" name="submit" value="Submit">  
</form>

<?php
echo "<h2>Your Input:</h2>";
echo $name;
echo "<br>";
echo $email;
echo "<br>";
echo $website;
echo "<br>";
echo $comment;
echo "<br>";
echo $gender;
?>

</body>
</html>
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
    <div style="text-align: center;">
  <canvas id="tapeworm" width="100" height="100" style="background-color:black; ">

</canvas>
<br />
coordinatesgame
<br />
  </div> 
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5345138253575439"
     crossorigin="anonymous"></script>

  
  
<div style="text-align: center">
      
  <br />
  <div style="text-align: center">

  
    
<!--
<div style="text-align: center">


<p>
<a href="http://www.java3d.org/" target="_blank" style="font-size: 32px" >
 <u>java3d.org</u>
</a>
  
</p>
  -->
  
  

</div>
 


  
  
  
  
<div>
<canvas id="scene" width="850" height="480" style="background-color: blue;" >
</canvas>
  <!--
<p>
<u>
<a href="https://www.khronos.org/webgl" target="_blank" style="font-size: 32px" ><cite>
created with > WebGL

</cite>
</a>
</u>
  
    </p>
-->
</div>
<br />
  <div class="separator" style="clear: both;"><img alt="" border="0" width="600" data-original-height="335" data-original-width="1600" src="https://blogger.googleusercontent.com/img/a/AVvXsEg4btF0ln4OZwuwnc6PapbTTJI3Vzc69w_1cv_Dp9Y3apvUcXg9bTcxS5Q9T8ZJCXjv6gv2o2CbDnQRsUwMjC4JqChSQ8wC_ldz5KmYmJE8sQlPs7Xascg2RpRw2ApoSjsQf_hTWOg3t6uBcdp2XcJnyPb7NqlgIIK8928CfxQrPKcDAKCqb3wAUS417w=s600"/></div>
<br /><br /><br /> 
  
  <!--
<div style="text-align: center;">
<p>
Distance = √((X<sub>1</sub> - X<sub>2</sub>)<sup>2</sup> + (Y<sub>1</sub>
- Y<sub>2</sub>)<sup>2</sup> + (Z<sub>1</sub> -
Z<sub>2</sub>)<sup>2</sup>)
-->
<br />
<br /><br /><br />
  <!--

-->
  
  
  <br />
  
<br />
  <br />
  <br />
  <br />
  
  
  <script>

  var cubeRotation = 0.0;

window.onload = main;

function main() {

  const canvas = document.querySelector('#scene');

  const gl = canvas.getContext('webgl') || canvas.getContext('experimental-webgl');  

  if (!gl) {

    alert('Unable to initialize WebGL. Your browser or machine may not support it.');

    return;

  }

  /* Vertex shader program

*/

  const vsSource = `

    attribute vec4 aVertexPosition;

    attribute vec4 aVertexColor;

    uniform mat4 uModelViewMatrix;

    uniform mat4 uProjectionMatrix;

    varying lowp vec4 vColor;

    void main(void) {

      gl_Position = uProjectionMatrix * uModelViewMatrix * aVertexPosition;

      vColor = aVertexColor;

    }

  `;

  // Fragment shader program

  const fsSource = `

    varying lowp vec4 vColor;

    void main(void) {

      gl_FragColor = vColor;

    }

  `;

  // Initialize a shader program; this is where all the lighting

  // for the vertices and so forth is established.

  const shaderProgram = initShaderProgram(gl, vsSource, fsSource);

  // Collect all the info needed to use the shader program.

  // Look up which attributes our shader program is using

  // for aVertexPosition, aVertexColor and also

  // look up uniform locations.

  const programInfo = {

    program: shaderProgram,

    attribLocations: {

      vertexPosition: gl.getAttribLocation(shaderProgram, 'aVertexPosition'),

      vertexColor: gl.getAttribLocation(shaderProgram, 'aVertexColor'),

    },

    uniformLocations: {

      projectionMatrix: gl.getUniformLocation(shaderProgram, 'uProjectionMatrix'),

      modelViewMatrix: gl.getUniformLocation(shaderProgram, 'uModelViewMatrix'),

    }

  };

  // Here's where we call the routine that builds all the

  // objects we'll be drawing.

  const buffers = initBuffers(gl);

  var then = 0;

  // Draw the scene repeatedly

  function render(now) {

    now *= 0.001;  // convert to seconds

    const deltaTime = now - then;

    then = now;

    drawScene(gl, programInfo, buffers, deltaTime);

    requestAnimationFrame(render);

  }

  requestAnimationFrame(render);

}

//

// initBuffers

//

// Initialize the buffers we'll need. For this demo, we just

// have one object -- a simple three-dimensional cube.

//

function initBuffers(gl) {

  // Create a buffer for the cube's vertex positions.

  const positionBuffer = gl.createBuffer();

  // Select the positionBuffer as the one to apply buffer

  // operations to from here out.

  gl.bindBuffer(gl.ARRAY_BUFFER, positionBuffer);

  // Now create an array of positions for the cube.

  const positions = [

    /* Red */

    3,0,0,

    0,0,-3,

    0,2,-2,

    2,2,0,

    /* orange */

    -3,0,0,

    0,0,-3,

    0,2,-2,

    -2,2,0,
    

    /* yellow */

    -3, 0, 0,

    0, 0, 3,

    0, 2, 2,

   -2, 2, 0,

    

    /* green */

    0, 0, 3,

    3, 0, 0,

  2, 2, 0,

  0, 2, 2,

    /* blue */

    3, 0, 0,

    0, 0, -3,

     0,  -2, -2,

     2,  -2, 0,

    /* indigo */

    0, 0, -3,

     -3, 0, 0,

     -2, -2, 0,

    0, -2, -2,

   /* violet */

    -3, 0, 0,

    0, 0, 3,

    0, -2, 2,

    -2, -2, 0,

    

    /* black */

    3, 0, 0,

    0, 0, 3,

    0, -2, 2,

    2, -2, 0,

    /* white */
    
  0,2,-2,
  -2,2,0,
  0,2,2,
  2,2,0,
    
  /* tenth */
  0,-2,-2,
  -2,-2,0,
  0,-2,2,
  2,-2,0,
    
    /* Tink */
  3,0,1,
  3,1,1,
  4,1,1,
  4,0,1,
    
   /* turquoise */
  3,1,0,
  3,2,0,
 4,2,0,
  4,1,0,

];

  // Now pass the list of positions into WebGL to build the

  // shape. We do this by creating a Float32Array from the

  // JavaScript array, then use it to fill the current buffer.

  gl.bufferData(gl.ARRAY_BUFFER, new Float32Array(positions), gl.STATIC_DRAW);

  // Now set up the colors for the faces. We'll use solid colors

  // for each face.

  const faceColors = [

  //* red */ 

    [.01, 0, .01, 1.0],

 /* orange */

    [.01, 0, .01, 1.0],   

  /* yellow */

    [.01, 0, .01,  1],    

 /*  green */

    [.01, 0, .01, 1],   

  /*   blue */

    [.01,  0,  .01,  1.0],    

 /* indigo */

    [ .01, 0, .01,  1.0],

     /* violet */

    [ .01, 0, .01,  1.0],

/* black */

    [ .01, 0, .01,  1.0],
    
/* white */
   [.01,0,.01,1.0],
/* tenth */
   [.01,0,.01,1.0],
    
/* Tink */
   [.01,0,.01,1.0],
     
/* turquoise */
   [.01,0,.01,1.0],
    
  ];

  // Convert the array of colors into a table for all the vertices.

  var colors = [];

  for (var j = 0; j < faceColors.length; ++j) {

    const c = faceColors[j];

    // Repeat each color four times for the four vertices of the face

    colors = colors.concat(c, c, c, c);

  }

  const colorBuffer = gl.createBuffer();

  gl.bindBuffer(gl.ARRAY_BUFFER, colorBuffer);

  gl.bufferData(gl.ARRAY_BUFFER, new Float32Array(colors), gl.STATIC_DRAW);

  // Build the element array buffer; this specifies the indices

  // into the vertex arrays for each face's vertices.

  const indexBuffer = gl.createBuffer();

  gl.bindBuffer(gl.ELEMENT_ARRAY_BUFFER, indexBuffer);

  // This array defines each face as two triangles, using the

  // indices into the vertex array to specify each triangle's

  // position.

  const indices = [

    0,  1,  2,      0,  2,  3,    // front

    4,  5,  6,      4,  6,  7,    // back

    8,  9,  10,     8,  10, 11,   // top

    12, 13, 14,     12, 14, 15,   // bottom

    16, 17, 18,     16, 18, 19,   // right

    20, 21, 22,     20, 22, 23,   // left

    24, 25, 26,     24, 26, 27,

/* carpet */

    28, 29, 30,     28, 30, 31,

/* tinkerbell */

    32, 33, 34,     32, 34, 35,
    
/* center */
    36,37,38,       36,38, 39,
/* tenth */
    40,41,42,       40,42,43,
/* Tink */
    44,45,46,		44,46,47,
/* turquoise */
    48,49,50,		48,50,51,

  ];

  // Now send the element array to GL

  gl.bufferData(gl.ELEMENT_ARRAY_BUFFER,

      new Uint16Array(indices), gl.STATIC_DRAW);

  return {

    position: positionBuffer,

    color: colorBuffer,

    indices: indexBuffer,

  };

}

//

// Draw the scene.

//

function drawScene(gl, programInfo, buffers, deltaTime) {

  gl.clearColor(0.1, 0.0, 0.1, 0.9);  // Clear to black, fully opaque

  gl.clearDepth(1.0);                 // Clear everything

  gl.enable(gl.DEPTH_TEST);           // Enable depth testing

  gl.depthFunc(gl.LEQUAL);            // Near things obscure far things

  // Clear the canvas before we start drawing on it.

  gl.clear(gl.COLOR_BUFFER_BIT | gl.DEPTH_BUFFER_BIT);

  // Create a perspective matrix, a special matrix that is

  // used to simulate the distortion of perspective in a camera.

  // Our field of view is 45 degrees, with a width/height

  // ratio that matches the display size of the canvas

  // and we only want to see objects between 0.1 units

  // and 100 units away from the camera.

  const fieldOfView = 45 * Math.PI / 180;   // in radians

  const aspect = gl.canvas.clientWidth / gl.canvas.clientHeight;

  const zNear = 0.1;

  const zFar = 100.0;

  const projectionMatrix = mat4.create();

  // note: glmatrix.js always has the first argument

  // as the destination to receive the result.

  mat4.perspective(projectionMatrix,

                   fieldOfView,

                   aspect,

                   zNear,

                   zFar);

  // Set the drawing position to the "identity" point, which is

  // the center of the scene.

  const modelViewMatrix = mat4.create();

  // Now move the drawing position a bit to where we want to

  // start drawing the square.

  mat4.translate(modelViewMatrix,     // destination matrix

                 modelViewMatrix,     // matrix to translate

                 [.5, 0, -15]);  // amount to translate

  mat4.rotate(modelViewMatrix,  // destination matrix

              modelViewMatrix,  // matrix to rotate

              cubeRotation,     // amount to rotate in radians

              [.5,1,.5]);       // axis to rotate around (Z)

  mat4.rotate(modelViewMatrix,  // destination matrix

              modelViewMatrix,  // matrix to rotate

              cubeRotation * 60,// amount to rotate in radians

              [1,1,0]);       // axis to rotate around (X)

  // Tell WebGL how to pull out the positions from the position

  // buffer into the vertexPosition attribute

  {

    const numComponents = 3;

    const type = gl.FLOAT;

    const normalize = false;

    const stride = 0;

    const offset = 0;

    gl.bindBuffer(gl.ARRAY_BUFFER, buffers.position);

    gl.vertexAttribPointer(

        programInfo.attribLocations.vertexPosition,

        numComponents,

        type,

        normalize,

        stride,

        offset);

    gl.enableVertexAttribArray(

        programInfo.attribLocations.vertexPosition);

  }

  // Tell WebGL how to pull out the colors from the color buffer

  // into the vertexColor attribute.

  {

    const numComponents = 4;

    const type = gl.FLOAT;

    const normalize = false;

    const stride = 0;

    const offset = 0;

    gl.bindBuffer(gl.ARRAY_BUFFER, buffers.color);

    gl.vertexAttribPointer(

        programInfo.attribLocations.vertexColor,

        numComponents,

        type,

        normalize,

        stride,

        offset);

    gl.enableVertexAttribArray(

        programInfo.attribLocations.vertexColor);

  }

  // Tell WebGL which indices to use to index the vertices

  gl.bindBuffer(gl.ELEMENT_ARRAY_BUFFER, buffers.indices);

  // Tell WebGL to use our program when drawing

  gl.useProgram(programInfo.program);

  // Set the shader uniforms

  gl.uniformMatrix4fv(

      programInfo.uniformLocations.projectionMatrix,

      false,

      projectionMatrix);

  gl.uniformMatrix4fv(

      programInfo.uniformLocations.modelViewMatrix,

      false,

      modelViewMatrix);

  {

    const vertexCount = 72;

    const type = gl.UNSIGNED_SHORT;

    const offset = 0;

    gl.drawElements(gl.TRIANGLES, vertexCount, type, offset);

  }

  // Update the rotation for the next draw

  cubeRotation += deltaTime;

}

//

// Initialize a shader program, so WebGL knows how to draw our data

//

function initShaderProgram(gl, vsSource, fsSource) {

  const vertexShader = loadShader(gl, gl.VERTEX_SHADER, vsSource);

  const fragmentShader = loadShader(gl, gl.FRAGMENT_SHADER, fsSource);

  // Create the shader program

  const shaderProgram = gl.createProgram();

  gl.attachShader(shaderProgram, vertexShader);

  gl.attachShader(shaderProgram, fragmentShader);

  gl.linkProgram(shaderProgram);

  // If creating the shader program failed, alert

  if (!gl.getProgramParameter(shaderProgram, gl.LINK_STATUS)) {

    alert('Unable to initialize the shader program: ' + gl.getProgramInfoLog(shaderProgram));

    return null;

  }

  return shaderProgram;

}

//

// creates a shader of the given type, uploads the source and

// compiles it.

//

function loadShader(gl, type, source) {

  const shader = gl.createShader(type);

  // Send the source to the shader object

  gl.shaderSource(shader, source);

  // Compile the shader program

  gl.compileShader(shader);

  // See if it compiled successfully

  if (!gl.getShaderParameter(shader, gl.COMPILE_STATUS)) {

    alert('An error occurred compiling the shaders: ' + gl.getShaderInfoLog(shader));

    gl.deleteShader(shader);

    return null;
  }
  return shader;
}
</script>
  
  </div>
 
         

 
  <br />
  
<script>

var c = document.getElementById("tapeworm");

var ctx = c.getContext("2d");

ctx.beginPath();

ctx.moveTo(20, 20);

ctx.bezierCurveTo(5, 50, 50, 60, 75, 80);

ctx.strokeStyle = "#FF0000";
ctx.lineWidth = "1";
ctx.lineCap = "round";
ctx.stroke();

</script>
   <div>
<canvas id="tapeworm1" width="100" height="100" style="float: left; clear: ; background-color:black; ">

</canvas>

  <br />
  
         

<script>

var c = document.getElementById("tapeworm1");

var ctx = c.getContext("2d");

ctx.beginPath();

ctx.moveTo(20, 20);

ctx.bezierCurveTo(80, 70, 25, 35, 50, 80);

ctx.strokeStyle = "#FF0000";
ctx.lineWidth = "1";
ctx.lineCap = "round";
ctx.stroke();

</script>
  
  
  
  <canvas id="tapeworm2" width="100" height="100" style="float: right ; background-color:black; ">

</canvas>

  <br />
  
         

<script>

var c = document.getElementById("tapeworm2");

var ctx = c.getContext("2d");

ctx.beginPath();

ctx.moveTo(20, 20);

ctx.bezierCurveTo(80, 30, 40,40, 30, 80);

ctx.strokeStyle = "#0000FF";
ctx.lineWidth = "1";
ctx.lineCap = "round";
ctx.stroke();

</script>
  </div>
  
  
         
<canvas id="arrow" width="100" height="100" style="background-color:black; border:1px solid #000000;">

   </canvas>
                 
  <script>
    var c = document.getElementById("arrow");
  var ctx = c.getContext("2d");
    
  ctx.beginPath();

ctx.moveTo(10,60);

ctx.lineTo(25,90);

ctx.strokeStyle = "gold";
ctx.lineWidth = "5";

ctx.stroke();
    
        

ctx.stroke();
        
ctx.beginPath();
ctx.moveTo(45,60);
ctx.lineTo(25,90);
ctx.strokeStyle = "gold";
ctx.lineWidth = "5";
ctx.stroke();
    
ctx.beginPath();
ctx.moveTo(35,10);
ctx.lineTo(25,90);
ctx.strokeStyle = "gold";
ctx.lineWidth = "5";
ctx.stroke();
    

    
   
  </script>
  
  
  
  

  
  
  
  
  
  
  
  
  
  
  <canvas id="arrow1" width="100" height="100" style="float: right; background-color:black; border:1px solid #000000;">

   </canvas>
                 
  <script>
    var c = document.getElementById("arrow1");
  var ctx = c.getContext("2d");
    
  ctx.beginPath();

ctx.moveTo(100,0);

ctx.lineTo(0,80);

ctx.strokeStyle = "gold";
ctx.lineWidth = "5";

ctx.stroke();
    
        

ctx.stroke();
        
ctx.beginPath();
ctx.moveTo(45,60);
ctx.lineTo(0,80);
ctx.strokeStyle = "gold";
ctx.lineWidth = "5";
ctx.stroke();
    
ctx.beginPath();
ctx.moveTo(35,10);
ctx.lineTo(0,90);
ctx.strokeStyle = "gold";
ctx.lineWidth = "5";
ctx.stroke();
    

    
   
  </script>





  
  <div id="bottom"></div>

</body>
</html>
  
