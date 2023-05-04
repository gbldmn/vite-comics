<script>

import SingleProduct from './SingleProduct.vue'

export default{
    name: "MainComp",
    components: {
        SingleProduct
    },
    data(){
        return{
           cards: [
  {
    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
    "price": "$2.99",
    "series": "Batman Beyond",
    "type": "comic book"
  },
  {
    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
    "price": "$3.99",
    "series": "Batman/Superman",
    "type": "comic book"
  },
  {
    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
    "price": "$4.99",
    "series": "Batman/Superman Annual",
    "type": "comic book"
  },
  {
    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
    "price": "$5.99",
    "series": "Batman: The Joker War Zone",
    "type": "comic book"
  },
  {
    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
    "price": "$6.99",
    "series": "Batman: Three Jokers",
    "type": "comic book"
  },
  {
    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
    "price": "$4.99",
    "series": "Batman: White Knight Presents",
    "type": "comic book"
  },
  {
    "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
    "price": "$16.99",
    "series": "Catwoman",
    "type": "graphic novel"
  }
]
        }
    }
}
</script>

<template>
 <div class="container">
    <main>
        <button class="sas">CURRENT SERIES</button>
        <SingleProduct v-for="(elem, index) in cards" :key="index"
        :dettagliCard="elem"/>
        <button class="but">LOAD MORE</button>
    </main>
 </div>
 <div class="container2">
    <div class="schede">
        
            <li>
                <img src="/img/buy-comics-digital-comics.png" width="30px" alt="">
                <span>digital comics</span>
            </li>
            <li>
                <img src="/img/buy-comics-merchandise.png" width="30px" alt="">
                <span>dc merchandise</span>
            </li>
            <li>
                <img src="/img/buy-comics-subscriptions.png" width="30px" alt="">
                <span>subscription</span>
            </li>
            <li>
                <img src="/img/buy-comics-shop-locator.png" width="30px" alt="">
                <span>comic shop locator</span>
            </li>
            <li>
                <img src="/img/buy-dc-power-visa.svg" width="30px" alt="">
                <span>dc power visa</span>
            </li>
        
    </div>
 </div>
 <div class="container3">
  <div class="item">
    <div class="m-l">
        <ul>
            <li class="white">DC COMICS</li>
            <li><a href="">Charactes</a> </li>
            <li><a href="">Comics</a> </li>
            <li><a href="">Movie</a> </li>
            <li><a href="">Tv</a> </li>
            <li><a href="">Games</a> </li>
            <li><a href="">videos</a> </li>
            <li><a href="">News</a></li>
        </ul>
        <ul>
            <li class="white">SHOP</li>
            <li><a href="">Shop dc</a> </li>
            <li><a href="">Shop dc collectible</a> </li>
        </ul>
    </div>
    <div class="m-l">
        <ul>
            <li class="white">DC</li>
            <li><a href="">Terms of use</a> </li>
            <li><a href="">Privacy policy</a> </li>
            <li><a href="">Advertising</a> </li>
            <li><a href="">Jobs</a> </li>
            <li><a href="">Subscriptcions</a> </li>
            <li><a href=""> Talent workshops</a></li>
            <li><a href="">CPSC certificates</a> </li>
            <li><a href="">Ratings</a> </li>
            <li><a href="">Shop help</a> </li>
            <li><a href="">Contact us</a> </li>
        </ul>
    </div>
    <div class="m-l">
        <ul>
            <li class="white">SITES</li>
            <li><a href="">Dc</a> </li>
            <li><a href="">MAD magazine</a> </li>
            <li><a href=""> Dc kids</a></li>
            <li><a href="">Dc universe</a> </li>
            <li><a href="">Dc power visa</a> </li>
        </ul>
    </div>
  </div>
    <div class="absolute">
        <img src="/img/dc-logo-bg.png" width="500px"  alt="">
    </div>
 </div>
</template>