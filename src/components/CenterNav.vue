<template>
    <div>
        <nav>
            <ul>
                <li><a href="">First Link</a></li>
                <li><a href="">Second Link</a></li>
                <li><a href="">Third Link</a></li>
                <li><a href="">Fourth Link</a></li>
            </ul>
        </nav>
    </div>
</template>

<script>
    export default {
        name : 'SideNav'
    }
</script>

<style scoped>
ul{
    list-style: none;
}
a{
    position: relative;
    left: 0;
    color: gold;
}
</style>