<template>
    <div v-for="task in tasks">
        <h3>{{task.text}}</h3>
    </div>
</template>

<script>
export default {
    name: 'Tasks'

}
</script>