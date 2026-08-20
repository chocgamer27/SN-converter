---
layout: default
---

[Link to GitHub Repo](https://github.com/chocgamer27/SN-converter).

<textarea id="myInput" placeholder="Please enter your scientific notation or something to be turned into one!"></textarea>

<button onclick="getText()">Submit</button>

<pre id="output"><code></code></pre>

<style>
    #output {
        white-space: pre-wrap;
        overflow-wrap: break-word;
    }
    #myInput {
    resize: none
    width: 500px;
    height: 150px;
}
</style>

<script>
function getText() {
    const text = document.getElementById("myInput").value;
    document.getElementById("output").textContent = text;
}
</script>
