<template>
    <div>
        <ul>
            <li v-for="linkobj in linkNames">
                <a href="#">{{linkobj.name}}</a>
            </li>
        </ul>
    </div>
</template>
<script>
export default {
    name: "NavLink",
    props: {
        navLink : Object
    },
    data(){
        return{
            linkNames: [
                {
                    name: "Cibo per cani"
                },
                {
                    name: "Cibo per Pokémon"
                },
                {
                    name: "Cibo per Criceti"
                }
            ]
        }
    }
}
</script>
<style lang="scss" scoped>
    
</style>