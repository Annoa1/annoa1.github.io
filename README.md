## Welcome to GitHub Pages

<script>
function cb(response) {
    document.getElementById('visits').innerText = response.value;
}
</script>
<script async src="https://api.countapi.xyz/hit/annoa1.github.io//visits?callback=cb"></script>

<div>Test <span id="visits">...</span></div>

