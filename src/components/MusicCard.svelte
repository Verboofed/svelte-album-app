<script>
  export let albumTitle = '';
  export let artist = '';
  export let rating = '0.0/10'

</script>

<div class="card ">
  <img src="../src/img/{albumTitle}.png" alt="{albumTitle}">
   <div class="m-4">
     <span class="text-primary-400">{albumTitle}</span>
     <span class="block text-primary-400 text-sm">{artist}</span>
     <span class="block text-primary-400 text-sm">{rating}</span>
     <button href="/" class = "bg-primary-100 rounded px-2 mt-2 hover:bg-primary-600">View more</button>
   </div>
 </div>