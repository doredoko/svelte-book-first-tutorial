<header class="header">
  <a class="header-title" href="/">Svelte EC</a>
  <nav>
      <ul class="header-links">
          <li>ようこそゲストさん</li>
          <li>
              <a href="/cart">カート</a>
          </li>
      </ul>
  </nav>
</header>

<article class="product">
  <div class="product-main">
      <div class="image-container">
          <img src="https://github.com/svelte-book/sample-app/raw/main/static/svelte-book-1.png" alt="『Svelte Guide』表紙"/>
      </div>
      <div>
      <h2>Svelte Guide</h2>
          
      <dl>
          <dt>価格</dt>
          <dd>3500円</dd>
      </dl>
          <div>
              <button>カートに入れる</button>
          </div>
      </div>
  </div>
  <footer>
      <h3>関連商品</h3>
      <ul>
          <li>
              <a href="/products/react-book">React Book</a>
              - 3500円
          </li>
          <li>
              <a href="/products/vue-book">Vue Book</a>
              - 3500円
          </li>
          <li>
              <a href="/products/sngular-book">Angular Book</a>
              - 3500円
          </li>
      </ul>
  </footer>
</article>
<style>
  :global(body) {
      margin: 0;
      background-color: #eee;
      padding: 0;
  }

  .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin:  0 auto;
      background-color: #fff;
      padding: 0 15px;
      width: 100%;
      min-width: 800px;
      height: 50px;
  }
  .header-title {
      font-weight: bold;
  }
  .header-links {
      display: flex;
      gap: 10px;
      margin: 0;
      padding: 0;
      list-style: none;
  }

  .product {
      margin: 0 auto;
      background-color: #fff;
      padding: 15px;
      width: 100%;
      max-width: 800px;
  }

  .product-main {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
  }

  .image-container {
      width: 100%;
      max-width: 400px;
      overflow: hidden;
  }

  .image-container img {
      widows: 100%;
  }
</style>