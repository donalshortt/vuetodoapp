<template>
    <div>
        <div v-for="todo in todos" :key="todo.id">
            <TodoItem />
        </div>
    </div>
</template>

<script>
    import TodoItem from "./TodoItem";

    export default {
        name: "Todos",
        components: {TodoItem},
        comments: {
            TodoItem
        },
        props: ["todos"]
    }
</script>

<style scoped>

</style>