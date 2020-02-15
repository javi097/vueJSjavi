<template>
    <ul>
        <todo-item 
            v-for="(todo,index) in todos"
            :key="index"
            :todo="todo">
        </todo-item>
    </ul>
</template>

<style scoped>

</style>