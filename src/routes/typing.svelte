<script>
    import Typewriter from 'svelte-typewriter'
</script>


<div class="absolute z-10 top-1/2 min-w-40 ml-16 text-white text-3xl">
    <span>we are </span>
    <Typewriter
    mode="loop"
    interval=80
    unwriteInterval=50
    element=span
    --cursor-color="white"
    >
        <span>builders</span>
        <span>learners</span>
        <span>a community</span>
        <span>advAIta</span>
    </Typewriter>
</div>


<style>
    @media (max-width: 700px) {
        div {
            margin-left: 2rem;
        }
    }
</style>
