## Welcome to GitHub Pages

<script>
function cb(response) {
    document.getElementById('visits').innerText = response.value;
}
</script>
<script async src="https://api.countapi.xyz/hit/annoa1.github.io//visits?callback=cb"></script>

Test : <div id="visits">...</div>

