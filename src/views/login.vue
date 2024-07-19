<template>
    <div>
    <div class="box">
        <div class="container2">
            </div>
        <div class="container">
            <h3 class="aa1">login</h3>
            <input class="aa" type="text" placeholder="email or phone number"><br><br>
            <input class="aa" type="password" placeholder="password"><br><br>
            <input class="a3" type="button" value="login"><br><br>
            <h3 class="color"><a href="url">forgetten password?</a></h3>
            <h3 class="create"> create an account</h3>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container{
    background-color:rgb(250, 236, 236);
    height: 200px;
    width: 200px;
    padding: 50px;
    padding-top: 70px;
    padding-left: 100px;
    box-shadow:1px 2px 1px 2px grey;
    margin-top:70px;
}
.heading{
    font-size: 40px;
    color: rgb(46, 46, 46);
}
.heading2{
    padding-right:70px;
}
.color{
    color: rgb(144, 144, 151);
    /* width: 100px; */
}
h3{
    font-size: 15px;
}
.container2{
    display: inline-block;
    height: 200px;
    font-weight: 100px;
}
.box{
    display: flex;
    justify-content: center;
    align-items: center;

}
.create{
    background-color: rgb(104, 214, 214);
    text-align: center;
}

</style>