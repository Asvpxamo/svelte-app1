<script>
    import Login from './login.svelte';   
</script>

<div class="container">
    <div class="grid">

        <h1>Welcome to my fitness app!</h1>

    </div>
    <Login />

</div>

<style>
    h1 {
        color: orangered;
        
    }
    .container {
        display: grid;
        justify-content: center;
        align-items: center;
    }
</style>