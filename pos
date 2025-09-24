<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>POS Page (Demo)</title>
  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:Arial, sans-serif}
    body{background:#f4f5f7;color:#333;}
    header{
      background:#2c3e50;color:#fff;padding:16px;font-size:20px;font-weight:bold;
    }
    .container{display:flex;flex-wrap:wrap;min-height:calc(100vh - 60px);}
    .sidebar{flex:1 1 220px;background:#34495e;color:#fff;padding:20px;}
    .sidebar h3{margin-bottom:12px;font-size:18px;border-bottom:1px solid rgba(255,255,255,0.2);padding-bottom:6px}
    .sidebar ul{list-style:none;margin-top:12px}
    .sidebar li{margin-bottom:8px;cursor:pointer}
    .sidebar li:hover{text-decoration:underline}

    .main{flex:3 1 480px;padding:20px;}
    .search-bar{margin-bottom:16px;}
    .search-bar input{width:100%;padding:10px;border:1px solid #ccc;border-radius:6px;font-size:14px;}

    .products{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:16px;}
    .product{background:#fff;border-radius:6px;box-shadow:0 2px 6px rgba(0,0,0,0.08);padding:12px;text-align:center;cursor:pointer;transition:transform .2s}
    .product:hover{transform:translateY(-3px)}
    .product img{width:100%;height:120px;object-fit:contain;border-radius:4px;margin-bottom:8px;background:#fafafa}
    .product h4{font-size:14px;margin-bottom:4px}
    .product p{font-size:13px;color:#666}

    .cart{flex:1 1 260px;background:#ecf0f1;padding:20px;border-left:2px solid #ddd;}
    .cart h3{margin-bottom:16px;font-size:18px;border-bottom:1px solid #ccc;padding-bottom:6px}
    .cart-item{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px}
    .cart-item span{font-size:14px}
    .total{margin-top:20px;font-size:16px;font-weight:bold;}
    .btn-checkout{margin-top:20px;background:#27ae60;color:#fff;border:none;padding:12px;width:100%;border-radius:6px;font-size:16px;cursor:pointer}
    .btn-checkout:hover{background:#219150}

    @media(max-width:900px){
      .container{flex-direction:column}
      .cart{border-left:none;border-top:2px solid #ddd}
    }
  </style>
</head>
<body>
  <header>POS System</header>
  <div class="container">
    <aside class="sidebar">
      <h3>Categories</h3>
      <ul>
        <li>Beverages</li>
        <li>Snacks</li>
        <li>Dairy</li>
        <li>Household</li>
        <li>More…</li>
      </ul>
    </aside>

    <main class="main">
      <h2 style="margin-bottom:16px">Products</h2>
      <div class="search-bar">
        <input type="text" placeholder="Search products...">
      </div>
      <div class="products">
        <div class="product">
          <img src="https://picsum.photos/seed/cola/200/150" alt="Cola Drink">
          <h4>Cola Drink</h4>
          <p>$2.50</p>
        </div>
        <div class="product">
          <img src="https://picsum.photos/seed/chips/200/150" alt="Chips Pack">
          <h4>Chips Pack</h4>
          <p>$1.20</p>
        </div>
        <div class="product">
          <img src="https://picsum.photos/seed/milk/200/150" alt="Milk Bottle">
          <h4>Milk Bottle</h4>
          <p>$0.99</p>
        </div>
        <div class="product">
          <img src="https://picsum.photos/seed/bread/200/150" alt="Bread">
          <h4>Bread</h4>
          <p>$1.50</p>
        </div>
      </div>
    </main>

    <aside class="cart">
      <h3>Cart</h3>
      <div class="cart-item"><span>Cola Drink</span><span>$2.50</span></div>
      <div class="cart-item"><span>Chips Pack</span><span>$1.20</span></div>
      <div class="total">Total: $3.70</div>
      <button class="btn-checkout">Checkout</button>
    </aside>
  </div>
</body>
</html>
