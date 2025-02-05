


<script>
    /* We have created a variable named "message" using $state().
       This makes "message" a reactive state variable.
    */

    let message = $state("Write something here");
</script>

<div class="container">
<h1>Verandert by gani </h1>
    <!-- This heading displays the current value of the "message" variable. -->
    <h1 class="message">{message}</h1>

    <!-- This input field is bound to the "message" variable.
         When the user types in the input, the "message" value updates,
         and the heading automatically reflects the change.
    -->
    <input type="text" bind:value={message}>

</div>
