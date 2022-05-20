<script>
import MusicCard from "../components/MusicCard.svelte";

  
</script>

  <main class="albumStorage">
   <div class="grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5">
       <!-- album cards -->

      <MusicCard albumTitle = {"Igor"} artist = {"Tyler, The Creator"} rating = {"9.7/10.0"}/>

      <MusicCard albumTitle = {"The Melodic Blue"} artist = {"Baby Keem"} rating = {"8.7/10.0"}/>

      <MusicCard albumTitle = {"Call Me If You Get Lost"} artist = {"Tyler, The Creator"} rating = {"9.7/10.0"}/>

      <MusicCard albumTitle = {"Flower Boy"} artist = {"Tyler, The Creator"} rating = {"9.7/10.0"}/>

      <MusicCard albumTitle = {"Donda"} artist = {"Kanye West"} rating = {"6.7/10.0"}/>

      <MusicCard albumTitle = {"Blonde"} artist = {"Frank Ocean"} rating = {"10.0/10.0"}/>

   </div>
 </main>
