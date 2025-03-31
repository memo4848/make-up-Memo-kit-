##Project:* Makeup Magic Kit

*Description:*  virtual makeup kit that allows girls to try on different makeup looks and share them with frien

*HTML Structure:*
<!-- Makeup Product Showcase -->
<div class="makeup-products">
  <h2>Makeup Products</h2>
  <ul>
    <li>
      <img src="eyeshadow.jpg" alt="Eyeshadow">
      <span>Eyeshadow</span>
    </li>
    <li>
      <img src="lipstick.jpg" alt="Lipstick">
      <span>Lipstick</span>
    </li>
    <li>
      <img src="blush.jpg" alt="Blush">
      <span>Blush</span>
    </li>
  </ul>
</div>

<!-- Virtual Try-On -->
<div class="try-on">
  <h2>Try On Makeup</h2>
  <form>
    <label>
      <input type="checkbox" id="eyeshadow" name="eyeshadow">
      <span>Eyeshadow</span>
    </label>
    <label>
      <input type="checkbox" id="lipstick" name="lipstick">
      <span>Lipstick</span>
    </label>
    <label>
      <input type="checkbox" id="blush" name="blush">
      <span>Blush</span>
    </label>
  </form>
</div>

<!-- Makeup Look Customization -->
<div class="customization">
  <h2>Customize Your Look</h2>
  <form>
    <label>
      <select id="eyeshadow-color" name="eyeshadow-color">
        <option value="pink">Pink</option>
        <option value="purple">Purple</option>
        <option value="blue">Blue</option>
      </select>
      <span>Eyeshadow Color</span>
    </label>
    <label>
      <select id="lipstick-color" name="lipstick-color">
        <option value="red">Red</option>
        <option value="pink">Pink</option>
        <option value="coral">Coral</option>
      </select>
      <span>Lipstick Color</span>
    </label>
  </form>
</div>

<!-- Shareable Makeup Looks -->
<div class="share">
  <h2>Share Your Look</h2>
  <button>Share on Social Media</button>
</div>
<!-- Makeup Magic Kit -->

<style>
  /* Global Styles */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
  }

  /* Makeup Product Showcase */
  .makeup-products {
    background-color: #fff;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .makeup-products ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .makeup-products li {
    display: inline-block;
    margin-right: 20px;
  }

  .makeup-products img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    object-fit: cover;
  }

  /* Virtual Try-On */
  .try-on {
    background-color: #fff;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .try-on form {
    margin-top: 20px;
  }

  .try-on label {
    display: block;
    margin-bottom: 10px;
  }

  /* Makeup Look Customization */
  .customization {
    background-color: #fff;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .customization form {
    margin-top: 20px;
  }

  .customization label {
    display: block;
    margin-bottom: 10px;
  }

  /* Shareable Makeup Looks */
  .share {
    background-color: #fff;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  .share button {
    background-color: #4CAF50;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }

  .share button:hover {
    background-color: #3e8e41;
  }
</style>



