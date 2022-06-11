<template>
    <div class="container">
        <img :src="image_character" alt="img">
        <p>{{name_character}}</p>   
    </div>    
</template>

<script>
export default {
    name: 'Image-comp',
    props: {
        image_character:{
            type:String,
            require:true,
        },
        name_character:{
            type:String,
            require:true,
        }
    },
    data: function(){
        return {}
    },
    // computed: {},
    //methods: {}
    // watch: {},
    // components: {},
    // mixins: [],
    // filters: {},
    // -- Lifecycle Methods
    // -- End Lifecycle Methods
}
</script>

<style scoped>

.container{
    display: flex;
    padding: 20px 10px;
    margin: 0 40px;
}

img{
    border-radius: 50%;
    width: 150px;
    height: 150px;
    margin-right: 15px;
    border-style: solid;
    border-color: rgb(25, 133, 25);
}

p{
    color: rgb(25, 133, 25);
    font-size: 40px;
    font-weight: bolder;
    align-self: center;
}
    
</style>