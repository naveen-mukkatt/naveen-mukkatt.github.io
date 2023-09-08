<script lang="ts">
    let count = 0;
    function incrementCount() {
        count += 1;
    }
    
    function decrementCount() {
        count -= 1;
    }

</script>

<h1> NAVEEN MUKKATT </h1>

<p>This is my website, which is a huge WIP right now.</p>
<p>I'm trying to get SvelteKIT to deploy to Pages probably
    and it's a massive pain.</p>

<h3>Count = {count}</h3>
<button on:click={incrementCount}>
    Increment
</button>

<button on:click={decrementCount}>
    Decrement
</button>

