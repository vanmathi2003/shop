<template>
  <div>
    <nav class="navbar">
    <h1>papzz shopping</h1>
    <div class="navbar-links">
        <p class="navbar-link"><a href=" ">home</a></p>
        <p class="navbar-link"><a href=" ">collcetions</a></p>
        <p class="navbar-link"><a href=" ">contact</a></p>

    </div>
    <div class="navbar-menu-toggle" onclick="showNavbar()">
        <i class="fa-solid fa-magnifying-glass" ></i>
    </div>
</nav>

  <div class="footer">
        <div class="footer-container">
            <div class="footer-box">
                <h2 class="heading">papzz</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eveniet quisquam voluptatem culpa, ullam amet autem possimus esse voluptates temporibus repudiandae.</p>
           <div class="footer-icon-condainer">
            <i class="fa-brands fa-instagram" ></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-facebook"></i><br>

           </div>
            </div>
        </div><br>
        <p>@2024 papzz.com</p><br>
        <p>contact:9382902899</p><br>
    
  </div>
    <!--product  -->
  <div class="product-section">
    <from class="from-search">
<input type="text" id="search" placeholder="search">
<i class="fa-solid fa-magnifying-glass"></i>
<div class="products" id="product">
    <img src="https://source.unsplash.com/random/250x250/?fashion?3">
    <p>white shirt</p>
</div>
    </from>
  </div>
  </div>


</template>

<script>
export default {

}
</script>

<style>
.navbar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}
.navbar-links{
    display: flex;
    column-gap: 20px;
}
.navbar-links a{
    text-decoration: none;
    color: #1d232c;
}
.navbar-links:hover{
    text-decoration: underline;

}

.navbar-menu{
    display: none;
}
.footer{
    margin-top: 20px;
    padding: 40px;
    background-color: #1d232c;
    color: white;
}
.footer-icon-container{
    color: white;
}


</style>
