# Miles-per-hour-to-Kilometers-per-hour
<!DOCTYPE html>
<html>
<Miles per hour to Kilometers per hour
>MPH to KPH</Miles per hour to Kilometers per hour
>
<body>



<img src="C:\Users\Emilio Ramirez\Desktop\escuela\week20\primero\speed.jpg" width="200" height="200"><BR>

  <p>
    <label>MPH</label> 


    <input id="inputMPH" type="text"><BR><BR>

    <button onclick="speedConverter(getElementById('inputMPH').value)">MPH to KPH</button>
  </p>
  <p>KPH: <span id="outputKPH"></span></p>

<script>


//this function is to convert miles per hour in to kilometers per hour
    function speedConverter(1.609344) {
      valNum = parseFloat(1.609344);
      document.getElementById("outputKPH").innerHTML = valNum * 1.609344; // valNum / 1.609344;
    }




</script>

</body>
