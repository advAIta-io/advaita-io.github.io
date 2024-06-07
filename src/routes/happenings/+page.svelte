<script>
    import Video from "../video.svelte";
    import Navbar from "../navbar.svelte";

    let hover = false;

    function hoverHandle() {
        hover = !hover;
    }
</script>

<Navbar />

<Video />

<!-- TODO: on mobile excess cards cause scrolling and the video also scrolls with the cards, leaving a white space below. Fix that -->
<div class="container flex flex-wrap p-8 top-28 absolute gap-4">
    <!-- svelte-ignore a11y-no-static-element-interactions -->
    <div class="card w-96 shadow-xl glass hover:bg-base-100/30 duration-100 ease-in-out">
        <div class="card-body">
            <h2 class="card-title">Paper Reading: Hospital Agent Framework</h2>
            <p>Join Amith in our first offline meetup!</p>
            <p>Amith will be going through the paper (linked below) and also implement it on a smaller scale using Llama-3!</p>
            <p>Date: TBA soon!</p>
            <div class="card-actions justify-start">
                <!-- <a href="https://arxiv.org/abs/2405.02957" target="_blank"></a> -->
                <button formaction="https://arxiv.org/abs/2405.02957" class="btn btn-block btn-outline btn-accent">Paper</button>
            </div>
        </div>
    </div>
</div>

<!-- <div class="container flex flex-wrap p-8 top-28 absolute gap-4">
    <div id="card1" class="w-[400px] p-4 border-4 border-white/70 rounded-xl bg-black/70 text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, eveniet? Dolorem dignissimos maiores non delectus possimus dolor nulla repudiandae vitae provident quae, obcaecati ipsam unde impedit corrupti veritatis minima porro?
        <div>
            <button class="p-1 mt-[5px] bg-white text-black rounded-lg">Join now!</button>
        </div>
    </div>
    <div id="card2" class="w-[400px] p-4 border-4 border-white/70 rounded-xl bg-black/70 text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, eveniet? Dolorem dignissimos maiores non delectus possimus dolor nulla repudiandae vitae provident quae, obcaecati ipsam unde impedit corrupti veritatis minima porro?
        <div>
            <button class="p-1 mt-[5px] bg-white text-black rounded-lg">Join now!</button>
        </div>
    </div>
    <div id="card2" class="w-[400px] p-4 border-4 border-white/70 rounded-xl bg-black/70 text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, eveniet? Dolorem dignissimos maiores non delectus possimus dolor nulla repudiandae vitae provident quae, obcaecati ipsam unde impedit corrupti veritatis minima porro?
        <div>
            <button class="p-1 mt-[5px] bg-white text-black rounded-lg">Join now!</button>
        </div>
    </div>
    <div id="card2" class="w-[400px] p-4 border-4 border-white/70 rounded-xl bg-black/70 text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, eveniet? Dolorem dignissimos maiores non delectus possimus dolor nulla repudiandae vitae provident quae, obcaecati ipsam unde impedit corrupti veritatis minima porro?
        <div>
            <button class="p-1 mt-[5px] bg-white text-black rounded-lg">Join now!</button>
        </div>
    </div>
    <div id="card2" class="w-[400px] p-4 border-4 border-white/70 rounded-xl bg-black/70 text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, eveniet? Dolorem dignissimos maiores non delectus possimus dolor nulla repudiandae vitae provident quae, obcaecati ipsam unde impedit corrupti veritatis minima porro?
        <div>
            <button class="p-1 mt-[5px] bg-white text-black rounded-lg">Join now!</button>
        </div>
    </div>
    <div id="card2" class="w-[400px] p-4 border-4 border-white/70 rounded-xl bg-black/70 text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, eveniet? Dolorem dignissimos maiores non delectus possimus dolor nulla repudiandae vitae provident quae, obcaecati ipsam unde impedit corrupti veritatis minima porro?
        <div>
            <button class="p-1 mt-[5px] bg-white text-black rounded-lg">Join now!</button>
        </div>
    </div>
</div> -->


<style>
    @media (max-width: 700px) {
        .container {
            flex-direction: column;
            align-items: center;
        }
        /* #card1, #card2 {
            width: 80vw;
        } */
    }
</style>