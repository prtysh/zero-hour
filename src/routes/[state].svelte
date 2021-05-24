<script context="module">
    export async function preload (page){
        return {state: page.params["state"]}
    }
</script>

<script>
    import Blob from "../components/Blob.svelte";
    export let state;
</script>

<h1>{state}</h1>