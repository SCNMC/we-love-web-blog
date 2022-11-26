<script>
    export let title;
</script>

<header>
    <nav>
        <h1>{title}</h1>
    </nav>
</header>

<style>
    header{
        z-index: 999;
        border-bottom: 4px solid  white;
        margin: .1em 1em;
        transform: translateY(30%);
    }

    nav {
        display: flex;
        flex-direction: row;
        gap: 5em;
        color: white;
    }
    h1{
        color: white;
        font-size: 4em;
    }

</style>