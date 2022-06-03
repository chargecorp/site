<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
</canvas>
<t> Currently working on this site! </t>
<table>
  <tr>
    <th> Company Name </th>
    <th> Employee </th>
    <th> Number </th>
  <tr>
    <th> Ben </th>
    <th> QA Engineer </th>
    <th> 1 </th>
<table>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");

// Create gradient
var grd = ctx.createLinearGradient(0, 200, 600, 0);
grd.addColorStop(1, "red");


// Fill with gradient
ctx.fillStyle = grd;
ctx.fillRect(0, 0, 500, 500);
</script>
