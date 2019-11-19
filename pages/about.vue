<template>
    <div class="card">
        <div class="text-center">

  <b-spinner variant="primary" type="grow" label="Spinning"></b-spinner>

    </div>
    <div class="card-body">
        <h3 class="text-dark text-center">About this app</h3>
        <p>This app has no goal! It's just me playing around with nuxt js for
            the first time and being amazed by its simplicity
        </p>
    </div>
    </div>
    
</template>

<script>
export default {
    head() {
        return {
            title: 'About this app',
            meta: [
                {name: 'description', content: 'this is the about of my app'},
                {name: 'keywords', content:'nuxt'}
            ]
        }
    }
}
</script>