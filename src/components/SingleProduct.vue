<script>

export default{
    name: "SingleProduct",
    props: ['dettagliCard']
}
</script>


<template>
        <div>
            <img :src= "dettagliCard.thumb" alt=""> 
            <h3>{{ dettagliCard.series }}</h3>
        </div>
</template>