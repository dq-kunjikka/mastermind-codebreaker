<!DOCTYPE html>

<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>
    Code-breaker (SVCE)</title>

  <style media="screen">
    .colorpeg {
      width: 470px;
      height: 860px;
      background-color: silver;
      border-style: solid;
      border-radius: 10px;
      text-align: center;
      box-shadow: 2px 3px 8px grey;
    }

    .keypegs {
      background-color: #B2A08F;
      border-style: dotted;
      box-shadow: 12px 13px 22px black;
    }



    #red {
      background-color: red;
    }

    #green {
      background-color: green;
    }

    #yellow {
      background-color: yellow;
    }

    #blue {
      background-color: blue;
    }

    #orange {
      background-color: orange;
    }

    #violet {
      background-color: violet;
    }

    #black {
      background-color: black;
    }
  </style>

</head>

<body bgcolor=lightblue>
  <center>
    <div>
      <h1>Given color pegs</h1>
      <table border="1" bgcolor="silver">
        <tr>
          <td>RED</td>
          <td><input id="red" type="button"> </td>
        </tr>
        <tr>
          <td>GREEN</td>
          <td><input id="green" type="button"> </td>
        </tr>
        <tr>
          <td>YELLOW</td>
          <td><input id="yellow" type="button"> </td>
        </tr>
        <tr>
          <td>BLUE</td>
          <td><input id="blue" type="button"> </td>
        </tr>
        <tr>
          <td>ORANGE</td>
          <td><input id="orange" type="button"> </td>
        </tr>
        <tr>
          <td>VIOLET</td>
          <td><input id="violet" type="button"> </td>
        </tr>
      </table>
    </div>
  </center>
  <hr>
  <center>
    <div>
      <h5 color="tomato">KEY PEGS: Black & white </h5>
      <input type="button"> <input id="black" type="button">
    </div>
  </center>
  <hr>

  <center>
    <table border="1">
      <tr>
        <td align="center">CODE-BREAKER</td>
        <td align="center">CODE-MAKER (keypegs hints)</td>
      </tr>
      <tr>
        <td>

          <div class="colorpeg">
            <br>
            Step 1: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 2: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 3: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 4: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 5: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 6: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 7: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 8: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 9:<input type="color">
            <input type="color">
            <input type="color">
            <input type="color"><br><br><br><br>
            Step 10: <input type="color">
            <input type="color">
            <input type="color">
            <input type="color">

          </div>
        </td>


        <td>
          <div class="keypegs">
            step 1: <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>
            step 2: <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 3:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 4:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 5:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 6:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 7:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 8:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 9:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color"><br><br>
            <hr>step 10:
            <input type="color">
            <input type="color"><br>
            <input type="color">
            <input type="color">

          </div>
        </td>

      </tr>
    </table>
  </center>
  <h6> ASHISH KUMAR SINGH </h6>
</body>

</html>
