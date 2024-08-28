<script src="https://cdn.jsdelivr.net/gh/DeshiJS/DeshiJS@main/dev/v1.js" defer></script>

<div $data='{"count": 0}'>
<button $text="Clicked {$.count} {$.count <= 1 ? 'time' : 'times'}" on:click="incrementCount">Increase Count</button>
</div>
            
<script>
const $ = {}
function incrementCount() {
  $.count++;
  console.log($.count)
}
</script>
