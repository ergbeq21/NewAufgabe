



<script>
    let message = $state("Write something here");
</script>

<div class="container">



<h1 class="message">{message}</h1>

<input type="text" bind:value={message}>

</div>