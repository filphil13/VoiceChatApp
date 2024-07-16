<script>
  	export let serverName;
	export let serverImage;
</script>

<div class="inline-block px-3">
    <div
      class="w-64 h-64 max-w-xs rounded-lg shadow-md bg-white hover:shadow-xl transition-shadow duration-300 ease-in-out"
    >
        <img src={serverImage} alt="server" class="w-full object-cover" />
        <h1 class=" text-center">{serverName}</h1>
    </div>
  </div>