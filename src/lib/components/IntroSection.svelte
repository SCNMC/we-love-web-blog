<section>
    <h1>Latest blogs.</h1>
    <div>
		<slot />
	</div>
</section>

<style>
    section{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 3em;
    padding-top: 2em;
    margin: 1em 2em;

   }
   h1{
    border-bottom: 3px solid white;
    padding-bottom: .5em;
    color: white;
   }



   @media (min-width:50rem){
    section{
        margin: 1em 1em;
        margin-top: 4em;
       
    }
   
    div{
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 1.2em;
   }

    }
    @media (min-width:70rem){
        h1{
        font-size: 2em;
    }
        section{
            margin: 1em 6em;
            padding: 3em 5em;
        }

    }
   
      
</style>