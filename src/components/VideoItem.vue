<template>
    <a href="#" class="mb-7 group">
        <VideoItemTrumbnail :index="index" />
        <VideoItemInfo :index="index" />
    </a>
</template>

<script>
import VideoItemTrumbnail from './VideoItemTrumbnail.vue'
import VideoItemInfo from './VideoItemInfo.vue'

export default {
    components: {
        VideoItemTrumbnail,
        VideoItemInfo
    },
    props: ['index']
}
</script>