<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>BONJOUR BOUTIQUE</title>

    <!-- google font cdn link-->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/css?family=Homemade+Apple:regular" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Dela+Gothic+One:regular" rel="stylesheet" />
   
    <!--Stylesheet-->
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="images/fav-icon.png">
    <script src="https://unpkg.com/scrollreveal"></script>
  </head>
<body>

  
    <!--Navigation bar-->
    <nav class="navbar">

      <a href="#home"class="links">Home</a>
      <a href="#about"class="links"></i>About Us</a>
      <a href="#review"class="links"></i>Review</a>
      <a href="index2.html#shop"class="links"></i>Shop</a>
      <a href="#contact"class="links"></i>Contact Us</a>
  
      </nav>
     <a href=#logo class="links1">
     <img src="logo.jpg" class="img1"> 
     </a>

<!--background image animation-->
<section class="home" id="home">
<div class="bgimage">
    <div class="overlay"></div>
    <div class="content">
    <h1>BONJOUR BOTIQUE</span></h1>
    <p>Welcome to Bonjour Boutique. We specialize in curating a chic collection of clothing designed to make every moment unforgettable. Our pieces are tailored to celebrate your individuality and express your unique sense of fashion. Step in and say "Bonjour" to your new favorite style!</p>
      <a href="index2.html#shop"><button>SHOP NOW</button></a>
    </div>
</div>
</section>

<!-- About us -->
<section class="about" id="about">
    <div class="container">
      <h3 class="section-title">About Us</h3>
      <div class="content1">
        <div class="image">
          <img src="pp.jpg" alt="">
        </div>
        <div class="info">
          <h4 class="info-title">The Power Of FASHION</h4>
          <p>Fashion is more than clothing. It is a language that speaks without words. It has the power to express identity, transform confidence, and reflect individuality. A single outfit can tell a story, set a mood, or create a lasting impression. Harnessing the power of fashion means embracing its ability to shape how the world sees you, and how you see yourself.</p>
        </div>
      </div>
    </div>
</section>

<script>
  ScrollReveal({
    reset: true,
    distance: '60px',
    duration: 2000,
    delay: 350
  });

  ScrollReveal().reveal('.section-title',{delay:400, origin: 'left'});
  ScrollReveal().reveal('.image',{delay:400, origin: 'top'});
  ScrollReveal().reveal('.info',{delay:500, origin: 'bottom'});
  </script>
<!-- Products -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Display</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS -->
</head>
<body>
<section class="about" id="about">
      <div class="hot">
      <h3 class="section-title">HOT</h3>
    <div class="product-grid">
        <!-- Product 1 -->
        <div class="product-card">
            <img src="img5.jpg" alt="Product 1">
            <div class="product-info">
                <h3>Two Piece Set</h3>
                <p class="price">RM 62.90</p>
                <p class="description">The minimalist black dress exudes timeless elegance, while the classic white blouse adds a touch of refinement.</p>
                <a href="index2.html#shop" class="buy-btn">Buy Now</a>
            </div>
        </div>

        <!-- Product 2 -->
        <div class="product-card">
            <img src="img6.jpg" alt="Product 2">
            <div class="product-info">
                <h3>Casual Dog Run To Print Fun Loose Short Sleeve T-shirt</h3>
                <p class="price">RM 15.90</p>
                <p class="description">Made for comfort and style, this tee features a vibrant, whimsical dog run graphic that is perfect for dog lovers and anyone who enjoys a lighthearted vibe.</p>
                <a href="index2.html#shop" class="buy-btn">Buy Now</a>
            </div>
        </div>

        <!-- Product 3 -->
        <div class="product-card">
            <img src="img7.jpg" alt="Product 3">
            <div class="product-info">
                <h3>LABUBU T-shirt</h3>
                <p class="price">RM 17.99</p>
                <p class="description"> This quirky design showcases vibrant graphics that capture the fun and whimsical essence of Labubu, making it a standout piece for fans and casual wear enthusiasts alike.</p>
                <a href="index2.html#shop" class="buy-btn">Buy Now</a>
            </div>
        </div>
        <!-- Product 4 -->
        <div class="product-card">
            <img src="img8.jpg" alt="Product 3">
            <div class="product-info">
                <h3>Cargo Long Pants Elastic Loose Straight</h3>
                <p class="price">RM 22.70</p>
                <p class="description">Featuring a loose, straight-leg silhouette, these pants offer a perfect blend of functionality and fashion.</p>
                <a href="index2.html#shop" class="buy-btn">Buy Now</a>
            </div>
        </div>
        <!-- Product 5 -->
        <div class="product-card">
            <img src="img9.jpg" alt="Product 3">
            <div class="product-info">
                <h3>French Style Lace Skirt Women's Spring</h3>
                <p class="price">RM 22.60</p>
                <p class="description">Designed with delicate lace detailing, this skirt exudes a romantic and chic vibe, capturing the timeless allure of French fashion.</p>
                <a href="index2.html#shop" class="buy-btn">Buy Now</a>
            </div>
        </div>
        <!-- Order -->
                 <a href="index2.html#shop" class="see-btn">SEE MORE</a>
    </div>
</body>
</html>



<!--Reviews-->

<section class="review" id="review">

<h3 class="heading1">Customer's Review</h3>

<div class="box-container">
  
  <div class="box">
    <div class="stars">
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
    </div>
    <h2>Sandy Tan</h2>
    <p>I absolutely love shopping at this boutique! The collection is always stylish and unique, offering pieces that you would not find everywhere.</p>
  </div>

  <div class="box">
    <div class="stars">
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
    </div>
    <h2>Cindy Clark</h2>
    <p>Such a wonderful boutique! Every visit is a treat, the clothes are always on trend and of great quality.</p>
  </div>

  <div class="box">
    <div class="stars">
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
    </div>
    <h2>Alice Abigaile</h2>
    <p>This boutique never disappoints! The selection is always fresh and trendy, and I love the personalized service.</p>
  </div>

  <div class="box">
    <div class="stars">
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
      <i class="fas fa-star"></i>
    </div>
    <h2>Tania Takeda</h2>
    <p>I love how they curate their pieces, always on point with style and quality. Definitely my go-to boutique!</p>
  </div>
</div>

</section>

<script>
  ScrollReveal({
    reset: true,
    distance: '60px',
    duration: 2000,
    delay: 350
  });

  ScrollReveal().reveal('.heading1',{delay:400, origin: 'left'});
  ScrollReveal().reveal('.box-container',{delay:400, origin: 'top'});
</script>

<!--Contact Us-->
  <section class="contact" id="contact">
    <h1 class="heading3">Contact Us</h1>

    
<div class="ins-tile__body ins-tile__animated">
<h2 class="ins-tile__title">You can come to visit us!</h2><div role="heading" aria-level="2" class="ins-tile__description ins-tile__format">We are always happy to see you~</div>
<div class="ins-tile__row ins-tile__row--location"><div role="heading" aria-level="3" class="ins-tile__subheading">Our address:</div>
<div role="heading" aria-level="3" class="ins-tile__text ins-tile__address ins-tile__format">32, Jalan Lee Kwee Foh, Taman Canning, 31400 Ipoh, Perak</div><a class="ins-tile__text ins-tile__directions" role="link" href="https://www.google.com/maps/dir/?api=1&amp;destination=32%2C+Jalan+Lee+Kwee+Foh%2C+Taman+Canning%2C+31400+Ipoh%2C+Perak" target="_blank" rel="noopener noreferrer"><span class="ins-tile__directions-label"><span class="ins-tile__directions-label-inner">Get directions</span></span><svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19.76 11.44l-7.2-7.2a.773.773 0 00-1.12 0l-7.2 7.2c-.32.32-.32.8 0 1.12l7.2 7.2c.32.32.8.32 1.12 0l7.2-7.2c.32-.32.32-.8 0-1.12zm-6.263 2.812v-2.074H10.13v2.489H8.444v-3.319c0-.498.337-.83.843-.83h4.21V8.445l2.947 2.904-2.947 2.904z" fill="currentColor" fill-rule="evenodd"></path></svg></a></div><div class="ins-tile__row ins-tile__row--hours"><div role="heading" aria-level="3" class="ins-tile__subheading">Open hours:</div><div class="ins-tile__text ins-tile__hours-note ins-tile__format">Daily 10:00 AM to 9:00 PM</div></div><div class="ins-tile__row ins-tile__row--contacts"><div role="heading" aria-level="3" class="ins-tile__subheading">Contact info:</div><div class="ins-tile__text"><a aria-label="Call the store�s phone number" href="tel:+0123456789" class="ins-tile__phone"> +012-345 6789</a></div><div class="ins-tile__text"><a aria-label="Compose an email to the store" href="mailto:bonjourboutique@gmail.com" target="_self" class="ins-tile__email">bonjourboutique@gmail.com</a></div></div><div class="ins-tile__row ins-tile__row--social"><div class="ins-tile__row-inner"><!--[--><a href="https://facebook.com" title="Facebook" aria-label="Facebook" target="_blank" class="ins-tile__icon ins-tile__icon--outline-circle"><!----><!----><svg width="44" height="44" viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg" fill="none"><circle cx="22" cy="22" r="21.5" stroke="currentColor"></circle><path d="M32 22.0611C32 16.5045 27.5229 12 22 12C16.4771 12 12 16.5045 12 22.0611C12 27.0828 15.6568 31.2452 20.4375 32V24.9694H17.8984V22.0611H20.4375V19.8445C20.4375 17.323 21.9305 15.9301 24.2146 15.9301C25.3084 15.9301 26.4531 16.1266 26.4531 16.1266V18.6026H25.1922C23.95 18.6026 23.5625 19.3782 23.5625 20.1747V22.0611H26.3359L25.8926 24.9694H23.5625V32C28.3432 31.2452 32 27.0828 32 22.0611Z" fill="currentColor"></path></svg><!----><svg width="44" height="44" viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg"><circle cx="22" cy="22" r="22" fill="#1877F2"></circle><path d="M32 22.0611C32 16.5045 27.5229 12 22 12C16.4771 12 12 16.5045 12 22.0611C12 27.0828 15.6568 31.2452 20.4375 32V24.9694H17.8984V22.0611H20.4375V19.8445C20.4375 17.323 21.9305 15.9301 24.2146 15.9301C25.3084 15.9301 26.4531 16.1266 26.4531 16.1266V18.6026H25.1922C23.95 18.6026 23.5625 19.3782 23.5625 20.1747V22.0611H26.3359L25.8926 24.9694H23.5625V32C28.3432 31.2452 32 27.0828 32 22.0611Z" fill="white"></path></svg></a><a href="https://instagram.com" title="Instagram" aria-label="Instagram" target="_blank" class="ins-tile__icon ins-tile__icon--outline-circle"><!----><!----><svg width="44" height="44" viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg" fill="none"><circle cx="22" cy="22" r="21.5" stroke="currentColor"></circle><path d="M22 18.4703C20.0473 18.4703 18.4643 20.0506 18.4643 22C18.4643 23.9494 20.0473 25.5297 22 25.5297C23.9527 25.5297 25.5356 23.9494 25.5356 22C25.5356 20.0506 23.9527 18.4703 22 18.4703Z" fill="currentColor"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M16.3098 12.3139C20.061 11.8954 23.939 11.8954 27.6902 12.3139C29.7554 12.5443 31.4212 14.1689 31.6636 16.2379C32.1121 20.0662 32.1121 23.9338 31.6636 27.7621C31.4212 29.8311 29.7554 31.4557 27.6902 31.6861C23.939 32.1046 20.061 32.1046 16.3098 31.6861C14.2446 31.4557 12.5788 29.8311 12.3364 27.7621C11.8879 23.9338 11.8879 20.0662 12.3364 16.2379C12.5788 14.1689 14.2446 12.5443 16.3098 12.3139ZM27.4394 15.4836C26.8386 15.4836 26.3516 15.9699 26.3516 16.5697C26.3516 17.1695 26.8386 17.6557 27.4394 17.6557C28.0403 17.6557 28.5273 17.1695 28.5273 16.5697C28.5273 15.9699 28.0403 15.4836 27.4394 15.4836ZM16.8325 22C16.8325 19.1509 19.1461 16.8412 22 16.8412C24.8539 16.8412 27.1675 19.1509 27.1675 22C27.1675 24.8491 24.8539 27.1588 22 27.1588C19.1461 27.1588 16.8325 24.8491 16.8325 22Z" fill="currentColor"></path></svg><!----><svg width="44" height="44" viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg"><circle cx="22" cy="22" r="22" fill="url(#paint0_radial_2679_481)"></circle><circle cx="22" cy="22" r="22" fill="url(#paint1_radial_2679_481)"></circle><path d="M22 18.4703C20.0473 18.4703 18.4643 20.0506 18.4643 22C18.4643 23.9494 20.0473 25.5297 22 25.5297C23.9527 25.5297 25.5356 23.9494 25.5356 22C25.5356 20.0506 23.9527 18.4703 22 18.4703Z" fill="white"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M16.3098 12.3139C20.061 11.8954 23.939 11.8954 27.6902 12.3139C29.7554 12.5443 31.4212 14.1689 31.6636 16.2379C32.1121 20.0662 32.1121 23.9338 31.6636 27.7621C31.4212 29.8311 29.7554 31.4557 27.6902 31.6861C23.939 32.1046 20.061 32.1046 16.3098 31.6861C14.2446 31.4557 12.5788 29.8311 12.3364 27.7621C11.8879 23.9338 11.8879 20.0662 12.3364 16.2379C12.5788 14.1689 14.2446 12.5443 16.3098 12.3139ZM27.4394 15.4836C26.8386 15.4836 26.3516 15.9699 26.3516 16.5697C26.3516 17.1695 26.8386 17.6557 27.4394 17.6557C28.0403 17.6557 28.5273 17.1695 28.5273 16.5697C28.5273 15.9699 28.0403 15.4836 27.4394 15.4836ZM16.8325 22C16.8325 19.1509 19.1461 16.8412 22 16.8412C24.8539 16.8412 27.1675 19.1509 27.1675 22C27.1675 24.8491 24.8539 27.1588 22 27.1588C19.1461 27.1588 16.8325 24.8491 16.8325 22Z" fill="white"></path><defs><radialGradient id="paint0_radial_2679_481" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(11.6876 47.3889) rotate(-90) scale(43.6073 40.5582)"><stop stop-color="#FFDD55"></stop><stop offset="0.1" stop-color="#FFDD55"></stop><stop offset="0.5" stop-color="#FF543E"></stop><stop offset="1" stop-color="#C837AB"></stop></radialGradient><radialGradient id="paint1_radial_2679_481" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(-7.37023 3.16969) rotate(78.6806) scale(19.4926 80.3494)"><stop stop-color="#3771C8"></stop><stop offset="0.128" stop-color="#3771C8"></stop><stop offset="1" stop-color="#6600FF" stop-opacity="0"></stop></radialGradient></defs></svg></a><a href="https://twitter.com" title="X (former Twitter)" aria-label="X (former Twitter)" target="_blank" class="ins-tile__icon ins-tile__icon--outline-circle"><!----><!----><svg width="44" height="44" viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg" fill="none"><circle cx="22" cy="22" r="21.5" stroke="currentColor"></circle><path fill="currentColor" d="M24.043 20.47 30.57 13h-2.857l-4.985 5.7-4.3-5.7H12l7.271 9.675L12 31h2.857l5.743-6.585L25.571 31H32l-7.957-10.53Zm-8.5-5.685H17.6l10.857 14.46H26.4l-10.857-14.46Z"></path></svg><!----><svg width="44" height="44" viewBox="0 0 44 44" xmlns="http://www.w3.org/2000/svg"><circle cx="22" cy="22" r="22" fill="#000000"></circle><path fill="#fff" d="M24.043 20.47 30.57 13h-2.857l-4.985 5.7-4.3-5.7H12l7.271 9.675L12 31h2.857l5.743-6.585L25.571 31H32l-7.957-10.53Zm-8.5-5.685H17.6l10.857 14.46H26.4l-10.857-14.46Z"></path></svg></a><!--]--></div></div><!----></div>
</body>
</html>
