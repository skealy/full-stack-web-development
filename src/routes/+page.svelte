<script>
    import TodoItem from "$lib/todo-item.svelte";
    let titleName = 'Todo';
</script>

<svelte:head>
    <title>{titleName}</title>
</svelte:head>
<h1>{titleName}</h1>

<form action="" method="">
    <input type="text" name="text" aria-label="Add a todo" placeholder="+ type to add a todo">
</form>

<TodoItem/>
<TodoItem/>
<TodoItem/>


