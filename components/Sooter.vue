<template>
    <footer>
        <section class="finito">
            <div class="one">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quae neque quod blanditiis cum ducimus beatae laboriosam molestiae magnam corporis veritatis incidunt voluptatum perferendis pariatur delectus quia tempora excepturi, dignissimos dolor!</p>
                <button>Start Live Chat</button>
            </div>
            <div class="two">
                <p class="title">Company</p>
                <p>About</p>
                <p>Features</p>
                <p>Works</p>
                <p>Career</p>
            </div>
            <div class="three">
                <p class="title">Help</p>
                <p>Customer Support</p>
                <p>Delivery Details</p>
                <p>Terms and Conditions</p>
                <p>Privacy Policy</p>
            </div>
            <div class="four">
                <p class="title">Resources</p>
                <p>Free Ebooks</p>
                <p>Development Tutorial</p>
                <p>How to - Blog</p>
                <p>Youtube Playlist</p>
            </div>
            <div class="five">
                <p class="title">Extra Links</p>
                <p>Customer Support</p>
                <p>Delivery Details</p>
                <p>Terms and Conditions</p>
                <p>Privacy Policy</p>
            </div>
        </section>
        
    </footer>
</template>


<style scoped>
    footer{
        padding: 2rem 5rem;
    }
    .finito{
        display: grid;
        grid-template-columns: 2fr 1fr 1fr 1fr 1fr;
        column-gap: 1rem;
    }
    
    .title{
        font-weight: 500;
    }
    .one{
        margin-top: 2.5rem;
    }
    .one button{
        background: #2563EB;
        border-radius: 5px;
        padding: 5px 20px;
        border: none;
        color: white;
    }



    @media(max-width:567px){
        .finito{
        display: grid;
        grid-template-columns:1fr;
        column-gap: 1rem;
    }
        footer{
        padding: 2rem 10px;
        text-align: center;
    }
        .one{
        margin-top: 10px;
    }
    }


    @media(min-width:577px) and (max-width:1200px){
        footer{
        padding: 2rem 10px;
    }
    .one{
        margin-top: 0px;
    }
    }
</style>