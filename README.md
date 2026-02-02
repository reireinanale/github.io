<!DOCTYPE html>
<html>
<head>
   
</head>

<body style="background-color: lightblue;">

<table border="1" width="100%" style="border:2px solid black;">

    <tr height="100">
        <td align="center">
            <img src="myphoto.jpg" width="100">
        </td>

        <td align="center">
            Reina Le
        </td>

        <td align="center">
            816840
        </td>
    </tr>

    <tr height="100">
        <td align="center">
            <img src="monkey.jpg" width="100">
        </td>

        <td align="center">
            <img src="butterfly.jpg" width="100">
        </td>

        <td></td>
    </tr>

    <tr height="100">
        <td></td>
        <td></td>
        <td></td>
    </tr>

    <tr height="100">
        <td colspan="3" align="center">
            CSCI 165 – Winter
        </td>
    </tr>

</table>

<br><br>

<table width="100%">

<tr>

    <td width="25%" align="center">

        <button onclick="document.getElementById('showImg').src='myphoto.jpg'">
           Your own photo
        </button>

        <br><br>

        <button onclick="document.getElementById('showImg').src='bird.jpg'">
          Bird
        </button>

    </td>

    <td width="75%" align="center" style="border:2px solid black;">

        <h1>Display your selected image here:</h1>

        <ul>
            <li>Your own photo</li>
            <li>Tiger</li>
        </ul>
        
 <img id="showImg" width="200">

    </td>
</tr>

</table>

<br><br>

<div style="background-color:lightgreen; border:2px solid black;">

    <p style="font-family: Times New Roman; font-size: 30px;">
  My hometown is Vietnam:
    </p>

    <p style="font-family: Arial; font-size: 20px;">
Everything there is beautiful,
    </p>

    <p style="font-family: Courier New; font-size: 14px;">
And the food are awesome.
    </p>

<br><br>

</div>

</body>
</html>
