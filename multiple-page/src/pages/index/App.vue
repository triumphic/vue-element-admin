<template>
    <div>
        index页面{{msg}}
        <router-view></router-view>
    </div>
</template>
<script>
export default {
    data() {
        return {
            msg: 'index'
        }
    }
}
</script>
