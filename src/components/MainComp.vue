<script>
export default{
    name: "MainComp",
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
    "series": "Batman: White Knight Presents: Harley Quinn",
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
        <div v-for="(elem, index) in cards"
            :key="index">
            <img :src="elem.thumb" alt=""> 
            <h3>{{ elem.series }}</h3>
        </div>
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
            <li class="white">dc comics</li>
            <li>charactes</li>
            <li>comics</li>
            <li>movie</li>
            <li>tv</li>
            <li>games</li>
            <li>videos</li>
            <li>news</li>
        </ul>
        <ul>
            <li class="white">shop</li>
            <li>shop dc</li>
            <li>shop dc collectible</li>
        </ul>
    </div>
    <div class="m-l">
        <ul>
            <li class="white">dc</li>
            <li>terms of use</li>
            <li>privacy policy</li>
            <li>and choices</li>
            <li>advertising</li>
            <li>jobs</li>
            <li>subscriptcions</li>
            <li>talent workshops</li>
            <li>CPSC certificates</li>
            <li>ratings</li>
            <li>shop help</li>
            <li>contact us</li>
        </ul>
    </div>
    <div class="m-l">
        <ul>
            <li class="white">sites</li>
            <li>dc</li>
            <li>MAD magazine</li>
            <li>dc kids</li>
            <li>dc universe</li>
            <li>dc power visa</li>
        </ul>
    </div>
  </div>
    <div class="absolute">
        <img src="/img/dc-logo-bg.png" width="500px"  alt="">
    </div>
 </div>
</template>