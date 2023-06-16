<template lang="">
    <div>
        <ul>
            <AppHeaderLink v-for="liElement in liList"
            :navname = liElement.name
            :link = liElement.link />
        </ul>
    </div>
</template>
<!-- <script> -->
<script>
import AppHeaderLink from './AppHeaderLink.vue';

export default {
    components: {
        AppHeaderLink,
    },

    name: 'AppHeader',

    data() {
        return {
            nav: [
                {
                    name: 'A',
                    link: '#'
                },
                {
                    name: 'B',
                    link: '#'
                },
                {
                    name: 'C',
                    link: '#'
                },
                {
                    name: 'D',
                    link: '#'
                },
                {
                    name: 'E',
                    link: '#'
                },
            ]
        }
    },
    methods() {
    },
}		
</script>

<style lang="scss"></style> 