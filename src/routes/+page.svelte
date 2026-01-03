<script lang="ts">

    let cardCosts = [
        {name: "Heavy Fertilizer Usage", img: ""},
        {name: "", img: ""},
        {name: "", img: ""},

    ]

</script>

<header class="pb-1" style="background: rgb(228, 220, 201);">
    <br><br><br>
    <h1 class="relative z-2 text-center text-[#441f1f]">Ceylon Made Cinnamon</h1>
    <p class="relative z-2 text-[grey] text-center text-[21px]">"Helping societies by exporting cinnamon world wide."</p>
    <div class="">
        
        <div class="relative z-2 mx-auto overflow-hidden min-[1024px]:h-[700px] min-[1024px]:rounded-2xl min-[1076px]:w-[1050.41px] " >
                <img class="absolute z-1 right-2 top-2 w-10 min-[1024px]:scale-[1.2] opacity-80" src="icons/srilankaicon.webp" alt="icon">
                <img class="mx-auto min-[1024px]:rounded-2xl min-[1024px]:h-[700px] hover:scale-110 duration-300" src="cinnamon.webp" alt="cinnamon">
            </div>
    </div>

</header>

<section class="bg-[#441f1f] p-3">
    <br><br>
    <h2 class="text-center text-white" style="text-transform: capitalize;">Cost of purchasing cinnamon in markets</h2>
    <br>

    <div class="flex flex-row flex-wrap justify-center gap-5">

        {#each cardCosts as item}
            <div class="w-80 h-80 rounded-2xl bg-amber-50" style="background: rgb(228, 220, 201);">
                <p class="text-center">{item.name}</p>
                <div class="w-full h-full flex flex-col items-center justify-center">
                    <img src={item.img} alt="hello">

                </div>
            </div>
            
        {/each}

    </div>


</section>