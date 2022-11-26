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
        border-bottom: 4px solid  white;
        margin: .1em 1em;
        transform: translateY(29%);
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

    @media(min-width:70rem){
        header{
            transform: translateY(4%);
        }
        h1{
            font-size: 10em;
        }
    
    }

</style>