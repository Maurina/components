<template>
    <div>
        <ul class="list-group">
            <li class="list-group-item" :key ="index" v-for="index in 5">
                server #{{ index }}
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>