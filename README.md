the code is up there, just download it and launch it to your browser, i recommend Chrome :)

Template (REMEMBER TO PUT THE PATH OR THE LINK OF THE IMAGE ON "path/or/link/to/your/image"):

<!DOCTYPE html>
<html>
<head>
<title>Rotating Image Animation</title>
<style>
body {
  margin: 0; /* remove default body margins */
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* fills viewport height */
}

.rotating-image {
  animation: rotate 1s linear infinite;
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
</style>
</head>
<body>
<div class="container">
  <img src="path/or/link/to/your/image" class="rotating-image" alt="Rotating Image">
</div>
</body>
</html>
