<script lang="ts">
    import {page} from "$app/stores"
    import "./Footer.scss"

    let FooterItems = [
        {path: "/products", name: "Products"},
        {path: "/contact", name: "Contact"},

    ]
</script>



<footer class="bg-[#6d6027] pt-3">
    <div class="w-full flex justify-center gap-[60px]">

        <div class="w-[300px] h-[300px] flex flex-col justify-center items-center">
            <a href="/">
                <p class="text-amber-100 text-[29px]">D&D Ceylon Cinnamon</p>
            </a>
            <p></p>
        </div>
        <div class="bg-amber-400 w-[300px] h-[300px] "></div>


    </div>

</footer>
