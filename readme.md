1. install using npm install simple-image-slider-interval-configurables 
//*install using command prompt inside your project, do not using gitbash.. i dont know how it wont works if install using gitbash 
2. set your jquery file inside html title or place it outside above your html body closing tag. dont forget to place the valid jquery
3. set your main.js/index.js where your javascript codes run
4. since this is a slider that is switch the active's class value, place your .active class value on first img elements 
5. you can customize the settings of the sliders
6. set the class of .right-button for next button click and .left-button for previous button click
7. you can also use bullet ticks if you want by adding the css codes below into your sass/css code 
//example:
<script>$('.container').imageSlider({
    interval: 5000, 
    slide: 'auto' / 'stop', 
    //(interval: place any value you want to determine the time slide change pictures frequently)
    //(slide: place 'auto' value to make the images changing base on interval time. and place 'stop' value to make thee images stop changing and only changes base on click)
    //use $('.container') for your image container
     

})
</script>
/*
css
.bullets {
    width: 200px;
    margin: 0 auto;
    text-align: center;
    position: relative;
    bottom: 30px;
    z-index: 300;

    .bullet {
        background-color: red;
        display: inline-block;
        width: 10px;
        height: 10px;
        border-radius: 5px;
        background: #333;
        margin: 0 5px;
        cursor: pointer;
        
    }
    .active{
        background: #ccc;
    }
    
} 
*/
