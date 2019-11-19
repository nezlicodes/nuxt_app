<template>
    <div class="card">
    
    <p class="card-body">  You can find me here <a href="https://twitter.com/nezlicodes">
    <font-awesome-icon :icon="['fab', 'twitter']" size = "lg"/> </a> 
    <a class="github" href="https://github.com/nezlicodes"><font-awesome-icon :icon="['fab', 'github']" size = "lg"/> </a>
 </p>
    
    </div>
</template>

<script>
export default {
    head() {
        return {
            title: 'Contact',
            meta: [
                {name: 'description', content: 'links to contact me'},
                {name: 'keywords', content:'twitter, github, nezlicodes'}
            ]
        }
    }
}
</script>

<style lang="css">
    .github{
        color: black
    }
</style>