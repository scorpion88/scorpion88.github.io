<script src="https://www.java.com/js/deployJava.js"></script>
<script>
	// using JavaScript to get location of JNLP
	// file relative to HTML page
	var dir = location.href.substring(0, location.href.lastIndexOf('/') + 1);
	var url = dir + "timeslotracker.jnlp";
	deployJava.createWebStartLaunchButton(url, '1.8.0');
</script>

# scorpion88.github.io
