# unit-convert
<!DOCTYPE html>
<html>
<title>Feet to Miles Length Converter</title>
<body>

<h2>Length Converter</h2>
<p>Type a value in the Feet field to convert the value to Miles:</p>

<p>
  <label>Feet</label>
  <input id="inputFeet" type="number" placeholder="Feet" oninput="LengthConverter(this.value)" onchange="LengthConverter(this.value)">
</p>
<p>Miles: <span id="outputMiles"></span></p>

<script>
function LengthConverter(valNum) {
  document.getElementById("outputMiles").innerHTML=valNum*0.00018939;
}
</script>
</body>
</html>
