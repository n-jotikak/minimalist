# Main Components

## Home Page

### Product Card

```javascript
<div class="card">
  <img src="./images/fur1.webp" alt="">
  <div class="overlay">
    <p class="price">From $180</p>
    <h3>Modern Chair</h3>
  </div>
</div>
```

## Subscribe Section Subscribe Form

```javascript
<section class="subscribe">
  <div class="subscribe-intro">
    <h2>Subscribe for a <span class="color">25% Discount</span></h2>
    <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Velit, accusamus? Officiis, debitis dolore officia eius in impedit, facere ea, cupiditate qui quidem sit sint perspiciatis alias suscipit ipsam! Soluta, quaerat?
    </p>
  </div>

  <form class="subscribe-form">
    <input type="email" placeholder="Enter your email">
    <button class="btn">Subscribe</button>
  </form>
</section>
```

## Shop Page

### Filter Aside

```javascript
<aside class="filter">
  <div class="category">
    <h4 class="title">Category</h4>
    <a href="#">Chairs</a>
    <a href="#">Beds</a>
    <a href="#">Furniture</a>
    <a href="#">Home Decor</a>
    <a href="#">Table</a>
    <a href="#">Accessories</a>
  </div>
  <div class="brand">
    <h4 class="title">Brand</h4>
    <label for="Amado">
      <input type="checkbox" name="brand" id="Amado" value="Amado"> Amado
    </label>
    <label for="Ikea">
      <input type="checkbox" name="brand" id="Ikea" value="Ikea"> Ikea
    </label>
    <label for="Artdeco">
      <input type="checkbox" name="brand" id="Artdeco" value="Artdeco"> Artdeco
    </label>
    <label for="Furn Inc">
      <input type="checkbox" name="brand" id="Furn Inc" value="Furn Inc"> Furn Inc
    </label>
    <label for="Minimalist">
      <input type="checkbox" name="brand" id="Minimalist" value="Minimalist"> Minimalist
    </label>
  </div>
</aside>
```

### Product Item

```javascript
<div class="product-item">
  <img src="./images/product1.webp" alt="">
  <div class="product-item-info">
    <p class="price">$180</p>
    <a href="product.html">Modern Chair</a>
    <div class="stars">
      <ion-icon name="star"></ion-icon>
      <ion-icon name="star"></ion-icon>
      <ion-icon name="star"></ion-icon>
      <ion-icon name="star"></ion-icon>
      <ion-icon name="star"></ion-icon>
    </div>
    <a href="product.html"><ion-icon name="cart-outline"></ion-icon></a>
  </div>
</div>
```

## Product Page

### Product Preview

```javascript
<section class="product-preview">
  <img src="./images/fur1.webp" alt="">
  <img src="./images/fur2.webp" alt="">
  <img src="./images/fur3.webp" alt="">
  <img src="./images/fur4.webp" alt="">
</section>
```

### Product Description

```javascript
<section class="product-detail">

  <div>
    <h2>Modern Chair</h2>
    <p class="price">$180</p>
  </div>

  <div>
    <h4>Description</h4>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam ratione suscipit quis labore aliquid dolor saepe, sapiente iusto iure totam porro aliquam minus nulla nesciunt officia deleniti. Tenetur, consequatur esse.
    </p>
  </div>

  <div>
    <h4>Material</h4>
    <ul>
      <li>Wood</li>
      <li>Ceramic</li>
      <li>....</li>
    </ul>
  </div>

</section>
```

### Product Review

```javascript
<div class="product-review">
  <img src="./images/profile-1.jpeg" alt="">
  <h4>Anna</h4>
  <div class="stars">
    <ion-icon name="star"></ion-icon>
    <ion-icon name="star"></ion-icon>
    <ion-icon name="star"></ion-icon>
    <ion-icon name="star"></ion-icon>
    <ion-icon name="star"></ion-icon>
  </div>
</div>
```
