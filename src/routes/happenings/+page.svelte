<script>
    import Video from "../video.svelte";
    import Navbar from "../navbar.svelte";
</script>


<Navbar />

<Video />

<!-- TODO: on mobile excess cards cause scrolling and the video also scrolls with the cards, leaving a white space below. Fix that -->
<div class="container flex flex-wrap p-8 top-28 absolute gap-4">
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
</div>


<style>
    @media (max-width: 700px) {
        .container {
            flex-direction: column;
            align-items: center;
        }
        #card1, #card2 {
            width: 80vw;
        }
    }
</style>