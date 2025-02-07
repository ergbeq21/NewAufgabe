

<script>
    // Destructuring "children" from $props() to allow component composition.
    let {children} = $props();

    // Importing an external CSS file for styling.
    import "../style.css"
</script>

<header>
    <!-- This is the header section of the page, displaying a static title. -->
    <nav class="navbar">
        <a href="#home">Home</a>
        <a href="#About us">About Us</a>
        <a href="#Contact">Contact</a>
    </nav>
</header>

<div class="body">
    <main>
        <!-- This renders any child components -->
        {@render children()}
    </main>
</div>

<footer>
    <!-- footer section with the author's name. -->
    Built by : Ergit Beqiri
</footer>
