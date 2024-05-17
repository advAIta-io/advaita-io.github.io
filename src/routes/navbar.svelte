<script>
    import logo from "$lib/assets/advaita-logo.png"
    import { base } from "$app/paths"
</script>

<nav class="text-xl text-[white] w-full font-bold absolute flex justify-around items-center">
    <a href="{base}/" class="hover:scale-105 duration-200">
        <img src={logo} alt="The advAIta logo" class="h-auto w-[130px] ml-10">
    </a>
    <ul class="flex justify-center gap-12">
        <!-- https://csstailwind.com/underline-on-hover-left-to-right-right-to-left-with-animation/ -->
        <li class="hover:scale-125 duration-300">
            <a href="{base}/" class="group transition-all duration-300 ease-in-out">
                <span class="bg-left-bottom bg-gradient-to-r from-orange-400 to-orange-400 bg-[length:0%_2px] bg-no-repeat group-hover:bg-[length:100%_2px] transition-all duration-500 ease-out">
                    Home
                </span>
            </a>
        </li>
        <li class="hover:scale-125 duration-300">
            <a href="{base}/happenings" class="group transition-all duration-300 ease-in-out">
                <span class="bg-left-bottom bg-gradient-to-r from-orange-400 to-orange-400 bg-[length:0%_2px] bg-no-repeat group-hover:bg-[length:100%_2px] transition-all duration-500 ease-out">
                    Happenings
                </span>
            </a>
        </li>
    </ul>
</nav>


<style>
    @media (max-width: 700px) {
        img {
            margin-left: 4px;
        }
        ul {
            gap: 20px;
        }
    }
</style>