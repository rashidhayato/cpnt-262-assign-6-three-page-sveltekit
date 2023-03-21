<h1>
  Some of our Gallery
</h1>

<main>
  
  <section class="gallery">
    <article>
      <img src="/images/cj.jpeg" alt="before">
      <h3>Before</h3>
    </article>
    <article>
      <img src="/images/cj-1.jpeg" alt="after">
      <h3>taper fade</h3>
    </article>
    <article>
      <img src="/images/hair-2.jpeg" alt="cut2">
      <h3>cut2</h3>
    </article>
    <article>
      <img src="/images/hair-3.jpeg" alt="cut3">
      <h3>cut3</h3>
    </article>
    <article>
      <img src="/images/haircut-1.jpeg" alt="cut4">
      <h3>cut4</h3>
    </article>
    <article>
      <img src="/images/haircut-4.jpeg" alt="cut5">
      <h3>cut5</h3>
    </article>
    <article>
      <img src="/images/haircut-5.jpeg" alt="cut6">
      <h3>cut6</h3>
    </article>
    <article>
      <img src="/images/argan-oil.jpeg" alt="cut7">
      <h3>cut7</h3>
    </article>
    <article>
      <img src="/images/haircut-6.jpeg" alt="cut8">
      <h3>cut8</h3>
    </article>
    <article>
      <img src="/images/inside-barbershop.webp" alt="inside look">
      <h3>inside look</h3>
    </article>
    <article>
      <img src="/images/hair-oil.png" alt="argan oil">
      <h3>argan oil</h3>
    </article>
    <article>
      <img src="/images/shop-products.jpeg" alt="inside look">
      <h3>inside look</h3>
    </article>

  </section>
</main>

<style>
  .gallery {
    margin: auto;
  }

  .gallery article {
    width: 100%;
    margin: 1rem;

    background-color: #cd0707;
    border-radius: 5rem;
    border: 1px solid #0707dd;
    box-shadow: 0 1px 1px #0000000d,
                0 2px 2px #0000000d,
                0 4px 4px #0000000d,
                0 8px 8px #0000000d;
  }

  .gallery article h3 {
    margin: 0.5rem;
    text-align: center;
  }

  .gallery article img {
    display: block;
    width: 100%;
    aspect-ratio: 1/1;
    object-fit: cover;

    border-top-left-radius: 1rem;
    border-top-right-radius: 1rem;
  }

  @media screen and (min-width: 800px) {
    .gallery {
      display: grid;
      grid-template-columns: 250px 250px 250px;
      justify-content: center;
      gap: 1rem;
    }

    .gallery article {
      margin: 0;
    }
  }

  h1, h2, h3, h4, h5, h6 {
  font-family: 'Smokum', cursive;
}

</style>