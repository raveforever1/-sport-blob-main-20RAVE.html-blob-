# shop-sport
shop sport on Github
<html><head><base href="Спортивнй магазин-1.html" />
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="main.css">
<title>Спортивный магазин RAVE</title>
<body>
  
<style>
  
  :root {
    --primary-color: #0066cc;
    --secondary-color: #00ff3c;
    --background-color: #f4f4f4;
    --text-color: #333;
  }
  
  body {
    font-family: 'Roboto', Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: var(--background-color);
    color: var(--text-color);
  }
  
  header {
    background-color: var(--primary-color);
    color: white;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .logo {
    font-size: 2rem;
    font-weight: bold;
  }
  
  nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
  }
  
  nav ul li {
    margin-left: 1rem;
  }
  
  nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
  }
  
  main {
    max-width: 6    200px;
    margin: 0 auto;
    padding: 2rem;
  }
  
  h1 {
    text-align: center;
    margin-bottom: 2rem;
  }
  
  .product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
  }
  
  .product-card {ц
    background-color: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
  }
  
  .product-card:hover {
    transform: translateY(-5px);
  }
  
  .product-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }
  
  .product-info {
    padding: 1rem;
  }
  
  .product-title {
    font-size: 1.2rem;
    font-weight: bold;
    margin-bottom: 0.5rem;
  }
  
  .product-price {
    font-size: 1.1rem;
    color: var(--primary-color);
    font-weight: bold;
  }
  
  .add-to-cart {
    display: block;
    width: 100%;
    padding: 0.5rem;
    background-color: var(--secondary-color);
    color: white;
    text-align: center;
    text-decoration: none;
    font-weight: bold;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  .add-to-cart:hover {
    background-color: #e68a00;
  }
  
  footer {
    background-color: var(--primary-color);
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
  }
  .checkout-btn {
        display: inline-block;
        background-color: #27ae60;
        color: white;
        padding: 0.75rem 1.5rem;
        text-decoration: none;
        border-radius: 4px;
        font-size: 1.1rem;
        margin-top: 1rem;
        transition: background-color 0.3s ease;
    }
    .checkout-btn:hover {
        background-color: #219a52;
    }

</style>
</head>
<body>
  <header>
    <div class="logo">Спортивный магазин RAVE</div>
    <nav>
      <ul>
        <li><a href="C:\Users\raved\Desktop\ИНТЕНЕТ МАГАЗИН\index.html\Магазин RAVE.html">Домой</a></li>
        <li><a href="C:\Users\raved\Desktop\ИНТЕНЕТ МАГАЗИН\index.html\Авторизация.html">Вход</a></li>
        <li><a href="C:\Users\raved\Desktop\ИНТЕНЕТ МАГАЗИН\index.html\Гольф.html">Гольф</a></li>
        <li><a href="C:\Users\raved\Desktop\ИНТЕНЕТ МАГАЗИН\index.html\Баскетбол.html">Баскетбол</a></li>

                <li><a href="https://2gis.ru/vilyujsk/firm/70000001043154457">Карта</a></li>
      </ul>
    </nav>
  </header>
  
  
  <main>
    <h1>Футбольное снаряжение</h1>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://ilandsport.ru/wa-data/public/shop/products/96/69/136996/images/187676/187676.970.jpg" alt="Official size football with leather texture and laces" width="250" height="220">
        <div class="product-info">
          <div class="product-title">Футбольные гольфы </div>
          <p>Футбольные носки Brondby IF Hummel</p>
          <p class="product-price">10.00$</p>
          <button class="add-to-cart">Добавить в корзину</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://avatars.mds.yandex.net/i?id=534d4e84795db026d9dd91bd0b383bffbe0e45b8-11932091-images-thumbs&n=13" alt="Black and white football cleats with studs" width="250" height="200">
        <div class="product-info">
          <div class="product-title">Футбольные бутсы</div>
          <p>Шиповки ZOOM VAPOR 15 ACADEMY MDS TF</p>
          <p class="product-price">$2.000</p>
          <button class="add-to-cart">Добавить в корзину</button>
        </div>
      </div>
      <div class="product-card">мммм
        <img src="https://page-images.websim.ai/High-performance%20running%20shoes%20with%20bright%20colors%20and%20cushioned%20soles_250x200xS2EU8oMOa4Tgu6xspx8805588dc504.jpg" alt="Red football helmet with face mask" width="250" height="200">
        <div class="product-info">
          <div class="product-title">Asics</div>
          <p>Мужские кроссовки Gel-Quantum 180 LS</p>
          <p class="product-price">$199.99</p>
          <button class="add-to-cart">Добавить в корзину</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://dealersport.ru/wp-content/uploads/2023/07/amazon-image-2023-2024-real-madrid-home-shirt-ronaldo-7-1687962615-475x0-1-409x409.png" alt="Blue football jersey with white number" width="250" height="200">
        <div class="product-info">
          <div class="product-title">Командная майка</div>
          <p>Футболка Роналду 7 Реал Мадрид 2023 – 2024</p>
          
          <p class="product-price">$79.99</p>
          <button class="add-to-cart">Добавить в корзину</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://dealersport.ru/wp-content/uploads/2023/08/роналду-шорты-409x409.jpg" alt="Set of football shoulder pads" width="250" height="200">
        <div class="product-info">
          <div class="product-title">Детская форма </div>
          <p>Реал Мадрид 2023 – 2024 Роналдо 7 белая</p>
          <p class="product-price">$149.99</p>
          <button class="add-to-cart">Добавить в корзину</button>
        </div>
      </div>
      <div class="product-card">
        <img src="https://static.cdek.shopping/images/shopping/g6xdPG7QklmtpWyF.webp" alt="Pair of football receiver gloves" width="250" height="200">
        <div class="product-info">
          <div class="product-title">Вратарские перчатки </div>
          <p>"Attract Resist Finger Support Junior" </p>
          <p class="product-price">$39.99</p>
          <button class="add-to-cart">Добавить в корзину</button>
          
        </div>
      </div>
    </div>
    
    <div class="cart-container">
      <h2>Ваша корзина</h2>
      <div class="cart-item">
          <img src="https://static.cdek.shopping/images/shopping/Yr1ExPOyCLwLva4Z.png" alt="High-perгformance running shoes with bright colors and cushioned soles" class="item-image" width="250" height="250">
          <div class="item-details">
              <h3 class="item-title">Бутсы Nike Force </h3>
              <p>Trout 9 Pro MCS Baseball Cleats, цвет White/Pure Platinum/Black</p>
              <p class="item-price">$129.99</p>
              <div class="item-quantity">
                  <button class="quantity-btn minus">-</button>
                  <input type="number" class="quantity-input" value="1" min="1">
                  <button class="quantity-btn plus">+</button>
                  <span class="item-remove">Удалить</span>
              
      </div>
      <div class="cart-summary">
          <p class="cart-total">Итого: $189.98</p>
          <a href="https://shop.sports-store.com/checkout" class="checkout-btn">Переходите с оформлением заказа</a>
      </div>
  </div>
</main>

 
</footer>
<script>
  document.addEventListener('DOMContentLoaded', function() {
      const cartItems = document.querySelectorAll('.cart-item');
 
      cartItems.forEach(item => {
          const minusBtn = item.querySelector('.minus');
          const plusBtn = item.querySelector('.plus');
          const quantityInput = item.querySelector('.quantity-input');
          const removeBtn = item.querySelector('.item-remove');

          minusBtn.addEventListener('click', () => {
              if (quantityInput.value > 1) {
                  quantityInput.value = parseInt(quantityInput.value) - 1;
                  updateTotal();
              }
          });

          plusBtn.addEventListener('click', () => {
              quantityInput.value = parseInt(quantityInput.value) + 1;
              updateTotal();
          });

          quantityInput.addEventListener('change', () => {
              if (quantityInput.value < 1) {
                  quantityInput.value = 1;
              }
              updateTotal();
          });

          removeBtn.addEventListener('click', () => {
              item.remove();
              updateTotal();
          });
      });

      function updateTotal() {
          let total = 0;
          cartItems.forEach(item => {
              const price = parseFloat(item.querySelector('.item-price').textContent.replace('$', ''));
              const quantity = parseInt(item.querySelector('.quantity-input').value);
              total += price * quantity;
          });
          document.querySelector('.cart-total').textContent = `Итого: $${total.toFixed(2)}`;
      }
  });
</script>
</body></html>
  </main>
  
  <footer>
    <p>&copy; 2024 Спортивная одежда все правы защищены.</p>
  </footer>
  
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      const addToCartButtons = document.querySelectorAll('.add-to-cart');
      
      addToCartButtons.forEach(button => {
        button.addEventListener('click', (event) => {
          const productInfo = event.target.closest('.product-info');
          const productTitle = productInfo.querySelector('.product-title').textContent;
          const productPrice = productInfo.querySelector('.product-price').textContent;
          
          alert(`Added to cart: ${productTitle} - ${productPrice}`);
          
          
        });
      });
    });
    
  </script>
</body></html>
