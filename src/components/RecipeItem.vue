<template>
    <div class="recipeItemContainer">
       <img :src="image">
        Mein Rezept
    </div>
</template>

<script>    
    export default {
        name: 'RecipeItem',
        data() {
            return {
                image: `https://www.edamam.com/assets/img/v.2.0/home_page_image_2.png`
            }
        },
    }


</script>

<style scoped>
    .recipeItemContainer{
        border: 1px solid rgba(0, 0, 0, 0.2);
        padding: 8px;
        border-radius: 8px;
        margin: 8px;
    }

</style>