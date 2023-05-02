<script>
    import "../app.css";
  </script>
  

  <div class="navbar text-center flex justify-center bg-white md:justify-start  md:bg-white">
    <img src="https://vppcoe-te.github.io/shinny-tiles/R%20CEILING%20LOGO-01.png" class="h-20 w-20" alt="">
    <h1>HEllo</h1>
  </div>


  <div
  class="navbar text-center flex justify-center bg-white md:justify-center md:bg-white border-t-2 border-purple-700"
  id="secnav"
>
  <ul class="mx-2 flex justify-center align-middle text-center text-purple-700 space-x-4">
    <li class="hover:text-white hover:bg-purple-700 p-2 mx-8 rounded-xl transition duration-150">
      <a href="/Home">Home</a>
    </li>
    <li class="hover:text-white hover:bg-purple-700 p-2 mx-8  rounded-xl transition duration-150">
      <a href="/Design">Design</a>
    </li>
    <li class="hover:text-white hover:bg-purple-700 p-2 mx-8 rounded-xl transition duration-150">
      <a href="/About">About</a>
    </li>
    <li class="hover:text-white  hover:bg-purple-700 p-2 mx-8 rounded-xl transition duration-150">
      <a href="/Contact">Contact</a>
    </li>
  </ul>
</div>


  <slot />

  <style>
    :global(body) {
      background-color: #f5f5f5 !important;
    }
  </style>