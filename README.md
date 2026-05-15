<h2 id="timer">Loading Link ... Wait 20 Seconds</h2>

<script>
let time = 20;

let x = setInterval(() => {
  time--;
  document.getElementById("timer").innerText =
    "Loading Link ... Wait " + time + " Seconds";

  if (time <= 0) {
    clearInterval(x);
    window.location.href = "https://google.com";
  }
}, 1000);
</script>
