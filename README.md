use NEw zip file
i added some new files in this



tr:nth-child(odd) { background-color: white; }
tr:nth-child(even) { background-color: gray; }
#to make consecutive rows colored



#timmer in java script
let timeLeft = 5;
let countdown = setInterval(() => {
  document.getElementById("timer").innerHTML = timeLeft + " seconds remaining";
  timeLeft--;
  if (timeLeft < 0) {
    clearInterval(countdown);
    window.location.href = "https://example.com";
  }
}, 1000);


#css some misc....
div { position: absolute; z-index: 100; }
display: grid;
grid-template-columns: 1fr 2fr;
grid-gap: 10px;



#responsive table 
<div style="overflow-x: auto;">
  <table>
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
      <th>Points</th>
