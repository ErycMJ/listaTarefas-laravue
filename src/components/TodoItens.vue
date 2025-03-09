<template>
    <div class="space-y-2">
        <TodoItem 
            v-for="todos in $store.state.todos"
            :key="todos.id"
            :todo="todos"
        />
    </div>
</template>

<script>
import TodoItem from './TodoItem.vue';

export default {
    components: { TodoItem }
}
</script>