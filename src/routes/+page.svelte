<svelte:head>
  <link href="https://fonts.googleapis.com/css2?family=Nabla&display=swap" rel="stylesheet"> 
</svelte:head>

<div class="hero">
  <p></p>
</div>

<style>

  .hero {
    font-size: 128px;
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;

    flex: auto;

    background-image: url('https://lh3.googleusercontent.com/p/AF1QipOgo90sEkdaVY5WIFB1Ir8HWDKHeOqNHuY7rhc_=s1360-w1360-h1020');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  } 

  .hero p {
    font-family: 'Nabla', Arial, Helvetica, cursive;
    font-size: clamp(64px, 10vw, 128px);
    margin: 0;
  }

</style>