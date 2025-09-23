<script>
    export default { 
        data() {
            return {
                width: '200',
                height: '200',
                myImg: '/assets/me.png'
            }
        },
    }
</script>

<template>

    <!-- add code here -->
     <!-- : is a shorthand notiation for v-bind -->
     <img :src="myImg" :width="width" :height="height">
   
</template>
