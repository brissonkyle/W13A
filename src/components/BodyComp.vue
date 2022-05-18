<template>
    <div>
        <CenterNav/>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste, 
            asperiores fugiat ipsum laboriosam accusamus beatae cupiditate ullam. 
            Repellat dolor ipsum et cupiditate necessitatibus odio? Quos voluptate asperiores
            obcaecati officiis, enim expedita ut unde natus quas ex similique eveniet doloribus 
            molestiae est maxime laboriosam delectus ipsum? Sequi, beatae dolore. Maiores, commodi.
        </p>
        <MeetUs/>
        <MeetMe/>
    </div>
</template>

<script>

import MeetUs from './MeetUs.vue'
import CenterNav from './CenterNav.vue'
import MeetMe from './MeetMe.vue'
    export default {
        name : 'BodyComp',
        components : {
            CenterNav,
            MeetUs,
            MeetMe,
        }
    }
</script>

<style scoped>
    p{
        color: gold;
    }
</style>