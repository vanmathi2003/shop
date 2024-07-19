<template>
  <div>
    <h2 style="padding: 20px;">New Arrival</h2>
<div class="new-arrival">
   <div class="new-arrival-container">
    <img src="https://source.unsplash.com/random/250x250/?fashion?1" alt="">
    <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
   </div> 

   <div class="new-arrival-container">
    <img src="https://source.unsplash.com/random/250x250/?fashion?2" alt="">
    <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
   </div>

   <div class="new-arrival-container">
    <img src="https://source.unsplash.com/random/250x250/?fashion?3" alt="">
    <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
   </div>

   <div class="new-arrival-container">
    <img src="https://source.unsplash.com/random/250x250/?fashion?4" alt="">
    <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
   </div> 
</div>
<div>
    <h2 style="padding: 20px;">Most-Wanted</h2>
    <div class="new-arrival">
       <div class="new-arrival-container">
        <img src="https://source.unsplash.com/random/250x250/?fashion?5" alt="">
        <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
       </div> 
       <div class="new-arrival-container">
        <img src="https://source.unsplash.com/random/250x250/?fashion?6" alt="">
        <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
       </div> 
    
       <div class="new-arrival-container">
        <img src="https://source.unsplash.com/random/250x250/?fashion?7" alt="">
        <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
       </div> 
    
       <div class="new-arrival-container">
        <img src="https://source.unsplash.com/random/250x250/?fashion?8" alt="">
        <button>shop Now<i class="fa-solid fa-arrow-right"></i></button>
       </div> 
    
</div>
</div>
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
 .new-arrival{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    
}
.new-arrivals{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    
}

.new-arrival-container{
    position: relative;
    flex-basis: 20%;

}
.new-arrival button{
    padding-left: 10px;
    padding-right: 10px;
    padding-top: 5px;
    padding-bottom: 5px;
    margin-top: 10px;
    color: #1d232c;
    position: absolute;
    top: 50%;
    left: 18%;
    border-radius: 10px;
    border: none;

} 

</style>
