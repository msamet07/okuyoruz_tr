<template>
<NavBar />
</template>

<script>

import NavBar from "@/components/NavBar.vue"

export default {
    name: "App",
    components : {
        NavBar
    },
    data() {
        return{
            message:"Merhaba",
            count:0,
            isVisible:true
        }
    }
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Mulish:wght@300;400;600;700&family=Open+Sans&family=Rubik+Iso&family=Satisfy&display=swap');
html,body {
font-family: 'Mulish', sans-serif;
/*font-family: 'Mulish', sans-serif;
font-family: 'Open Sans', sans-serif;
font-family: 'Rubik Iso', system-ui;
font-family: 'Satisfy', cursive;*/
}
</style>