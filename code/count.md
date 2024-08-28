<script src="https://cdn.jsdelivr.net/gh/DeshiJS/DeshiJS@main/dev/v1.js" defer></script>
<div $data='{"count": 10}'>
<p $text="{count}"></p>
<button on:click="incrementCount">Increase Count</button>
</div>
            
<script>
const $ = {}
function incrementCount() {
  $.count++;
}
</script>
