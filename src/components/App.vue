<template>
    <div class="px-3 py-10 md:px-10">
        <div class="w-full sm:w-1/2 lg:w-1/3 mx-auto">
            <TodoSpinner/>
            <TodoFormAdd/>
            <TodoItens/>
            <TodoEmpty/>
        </div>
    </div>
</template>

<script>
import TodoFormAdd from './components/TodoFormAdd.vue';
import TodoItens from './components/TodoItens.vue';
import TodoSpinner from './components/TodoSpinner.vue';
import TodoEmpty from './components/TodoEmpty.vue';

export default {
  name: 'App',
  components: {
    TodoSpinner,
    TodoFormAdd,
    TodoItens,
    TodoEmpty
  }
}
</script>