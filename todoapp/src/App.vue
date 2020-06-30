<template>
    <div id="app">
        <Todos />
    </div>
</template>

<script>
import Todos from './components/Todos';
export default {
    name: 'App',
    components: { Todos },
    data() {
        return {
            todos: [
                { id: 1, title: 'Learn Vue', completed: false },
                { id: 2, title: 'Learn more Vue', completed: false },
                { id: 3, title: 'Learn some more Vue', completed: false },
            ],
        };
    },
};
</script>

<style>
* {
    margin: 0;
    padding: 0;
}
</style>
