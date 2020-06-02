<template>
    <div>
        <p>Todo Item</p>
    </div>
</template>

<script>
    export default {
        name: "TodoItem"
    }
</script>

<style scoped>
    .todo_item {
        background-color: #2c3e50;
        color: whitesmoke;
        border-bottom: whitesmoke 1px dashed;
    }

    .is_complete {
        text-decoration: line-through;
    }

    .del {
        background-color: darkred;
        color: whitesmoke;
    }
</style>