<script>
    export let heroName;
</script>

<section>
    <h2>{heroName}</h2>
</section>



<style>

    section{
     background: #085EAA;
     background: linear-gradient(to bottom right, #085EAA, #AA4916);
     height: 78vh;
    display: flex;
    justify-content: end;
    align-items: end;
    z-index: -1;
    }

    h2 {
        font-size: 1.5em;
        color: white;
        margin-right: 1rem;
    }

    /* h2{
        font-size: 2em;
        margin-right:  .3em;
        margin-top: -1.2em;
        position: absolute;
        color: white;
    } */

    @media(min-width:70rem){
        section{
        margin-top: -5em;
        }
        h2{
            font-size: 3em;
        }
    }
</style>