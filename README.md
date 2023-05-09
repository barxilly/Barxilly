<h1 id="header">
  Ben Smith
</h1>



<script>
  // Change the innerHTML of the element with id="header" with a gradient change
  const header = document.getElementById("header");
  const htmls = [
    "Ben Smith",
    "Barxells",
    "Barx",
    "Boris Johnson II"
  ]
  // Change the innerHTML to those in that order for 2 seconds each infinitely
  let i = 0;
  setInterval(() => {
    header.innerHTML = htmls[i];
    i++;
    if (i == htmls.length) i = 0;
  }, 2000);
</script>