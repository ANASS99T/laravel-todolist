<template>

    <div class="todoListContainer">
        <div class="heading">
            <h2 class="title" id="title">Todo List</h2>
            <addItemForm />
        </div>
            <listView />
        
    </div>

</template>

<script>
import addItemForm from './components/addItemForm'
import listView from './components/listView'

export default {
    components: {
        addItemForm,
        listView
    }
}
</script>

<style scoped>
    .todoListContainer{
        width: 350px;
        margin:auto;
    }
    .heading{
        background:#e6e6e6;
        padding:10px;
    }
    .title{
        text-align:center;
    }
</style>