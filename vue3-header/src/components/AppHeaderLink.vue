<template>
    <li>
        <a :href=" link  ">
            {{ name }}
        </a>
    </li>
</template>

<script>
export default {
    name: 'AppHeader',
    props: {
        name: Name,
        link: Link,
    },
    data() {
        return {
        }
    },
    methods() {
    },
}		
</script>
<style scoped lang="scss">
</style> 