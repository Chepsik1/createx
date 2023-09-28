<script>
export default {

}
</script>

<template>
    <footer class=" container">
        <div class="item12">
            <div class="item1">
                <img src="../img/logo (1).svg" alt="">
                <img src="/public/images/whatsapp.svg" alt="">
                <img src="/public/images/messanger.svg" alt="">
                <img src="/public/images/facebook.svg" alt="">
                <img src="/public/images/twitter.svg" alt="">
                <img src="/public/images/you-tube.svg" alt="">
                <p>Createx Construction Bureau has been successfully operating in the USA construction market since 2000. We are proud to offer you quality construction and exemplary service. Our mission is to set the highest standards for construction sphere.</p>
            </div>
            <div class="item2">
                <h6 class="item_h6">Let’s stay in touch</h6>
                <input type="text" placeholder="Your email address ">
                <button>subscribe</button>
                <p>*Subscribe to our newsletter to receive communications and early updates from Createx Construction Bureau.</p>
            </div>
        </div>
        <div class="item45">
            <div class="item3">
                <h6 class="item_h6">HEAD OFFICE</h6>
                <address>
                    Address:<span>8502 Preston Rd. Inglewood, New York</span><br>
                    Call:<span>(405) 555-0128</span><br>
                    Email:<span>hello@createx.com</span>
                </address>
            </div>

            <div class="item4">
                <h6 class="item_h6">WHO WE ARE</h6>
                <nav>
                
                 <RouterLink to="/About us">About Us</RouterLink> <br>
                 <RouterLink to="/Contacts">Contacts</RouterLink><br>
                 <RouterLink to="/">Home</RouterLink>
                </nav>
            </div>
            <div class="item5">
                <h6 class="item_h6">OUR EXPERIENCE</h6>
                <nav>
                    <RouterLink to="/Services">Services</RouterLink><br>
        <RouterLink to="/Work">Work</RouterLink><br>
        <RouterLink to="/News">News</RouterLink>
                </nav>
            </div>
        </div>
        <div class="item67">
            <div class="item6">
                © All rights reserved. Made with <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none">
<path fill-rule="evenodd" clip-rule="evenodd" d="M7.99925 13.2715C4.93321 11.5252 3.22318 9.78955 2.39626 8.28361C1.54992 6.74228 1.62377 5.4441 2.0934 4.52273C3.05872 2.62892 5.80378 2.02333 7.4763 4.13865L7.99921 4.80001L8.52217 4.13868C10.195 2.02327 12.9402 2.62896 13.9055 4.52273C14.3751 5.44408 14.4489 6.74226 13.6025 8.28359C12.7756 9.78954 11.0654 11.5252 7.99925 13.2715ZM7.99928 2.73726C5.64647 0.501518 2.17555 1.42555 0.905488 3.91723C0.20846 5.2847 0.198939 7.05212 1.22753 8.92536C2.247 10.782 4.2796 12.7417 7.67675 14.6194L7.99924 14.7976L8.32173 14.6194C11.719 12.7417 13.7517 10.782 14.7712 8.92537C15.7999 7.05214 15.7904 5.28472 15.0934 3.91723C13.8233 1.4255 10.3523 0.501552 7.99928 2.73726Z" fill="#FF5A30"/>
</svg> by Createx Studio 
            </div>
            <div class="item7">
                <p>GO TO UP</p>
                <button><img src="/public/images/up-chevron.svg" alt=""></button>
                
            </div>

        </div>
    </footer>
</template>

<style style lang="scss">
.container {
    background: var(--gray-900, #1E212C);
    display: flex;
    flex-direction: column;
    max-width: 1920px;
    min-height: 565px;
    justify-content: space-evenly;
  
    flex-wrap: wrap;
    align-content: space-around;

}
.item6>svg{
    margin: 0 6px;
}

.item7>p{
    color: var(--white, #FFF);

/* small/regular */
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
margin: 0 16px 0 0;
}
.item7>button {
width: 40px;
height: 40px;
border-radius: 4px;
background: var(--primary, #FF5A30);

}

.item1 img:nth-child(1){
    margin-right:60px ;
}
.item1 img{
    margin: 0 16px 0 0;
}
.item2>h6{
    font-size: 24px;
}
.container a{
    color: var(--white, #FFF);
text-decoration: none;
/* base/regular */
font-family: Ubuntu;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 160%; /* 25.6px */
opacity: 0.6;
}

.item3>address span{
    color: var(--white, #FFF);

/* base/regular */
font-family: Ubuntu;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 160%; /* 25.6px */
opacity: 0.6;
}
.item3 address{
    color: var(--white, #FFF);

/* base/regular */
font-family: Ubuntu;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 160%; /* 25.6px */


}


.item_h6{
    color: var(--white, #FFF);

/* h6 */
font-family: Ubuntu;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 150%; /* 24px */
letter-spacing: 1px;
text-transform: uppercase;
margin: 13px 0 ;
}
.item12 {
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 242px;
}
.item2>input{
    width: 359px;
    height: 44px;
    border-radius: 4px;
border: 1px solid rgba(255, 255, 255, 0.20);
background: rgba(255, 255, 255, 0.12);
}
.item2 input::placeholder{
    color: var(--white, #FFF);

/* small/regular */
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
opacity: 0.6;
padding: 16px;
}

.item2>button{
    width: 131px;
    height: 44px;
    color: var(--white, #FFF);
text-align: center;
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 700;
line-height: 44px; /* 314.286% */
letter-spacing: 0.5px;
text-transform: uppercase;
border-radius: 0px 4px 4px 0px;
background: var(--primary, #FF5A30);
border: none;
}

.item2>p{
    color: var(--white, #FFF);

/* extrasmall/regular */
font-family: Ubuntu;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 18px */
opacity: 0.6;
margin: 16px 0 0;

}

.item45 {
    display: flex;
    justify-content: flex-start;
    gap: 150px;
}

.item1 {
    grid-area: auto;
   
   
    max-width: 493px;
}
.item1>p{
    color: var(--white, #FFF);

/* small/regular */
font-family: Ubuntu;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 21px */
opacity: 0.6;
margin: 24px 0 0;
}

.item2 {
  width: 495px;
}

.item3 {
   
}

.item4 {
  
}

.item5 {
   
}

.item6 {
    color: var(--white, #FFF);

/* extrasmall/regular */
font-family: Ubuntu;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 18px */
display: flex;
align-items: center;
}

.item7 {

display: flex;
align-items: baseline;
}

.item67 {
    display: flex;
    justify-content: space-between;
}</style>