<script lang="ts">

    let cardCosts = [
       
        {name: "Heavy fertilizer usage", img: "icons/heavy.webp", width: "250px", style: "rounded-[18px]",  card: "background: url('icons/heavy.webp') no-repeat;background-size: cover;"},
        {name: "Loss of flavour & smell", img: "icons/old.webp", width: "275px", style: "rounded-[18px]", card: "background: url('icons/old.webp') no-repeat;background-size: cover;"},
        {name: "More moisture, less oil ", img: "icons/water.webp", width: "250px", style: "rounded-[18px]", card: "background: url('icons/water.webp') no-repeat;background-size: cover;"},

    ]

</script>

<header class="pb-1" style="background: rgb(228, 220, 201);">
    <br><br><br>
    <h1 class="relative z-2 text-center text-[#441f1f]">Ceylon Made Cinnamon</h1>
    <p class="relative z-2 text-[grey] text-center text-[21px] m-3">"Helping societies by exporting cinnamon world wide."</p>
    <div class="">
        
        <div class="relative z-2 mx-auto overflow-hidden min-[1024px]:h-[700px] min-[1024px]:rounded-2xl min-[1076px]:w-[1051px] " >
                <img class="absolute z-1 right-2 top-2 w-10 min-[1024px]:scale-[1.2] opacity-80" src="icons/srilankaicon.webp" alt="icon">
                <img class="mx-auto w-full min-[1024px]:rounded-2xl min-[1024px]:h-[700px] hover:scale-110 duration-300" src="cinnamon.webp" alt="cinnamon">
            </div>
    </div>

</header>


<section class="bg-[#441f1f] pb-7">
    <div class="h-[20px] w-full"></div>
    <h2 class="text-center text-white" style="text-transform: capitalize;">Disadvantages of purchasing cinnamon in markets</h2>
    <br>

    <div class="flex flex-row flex-wrap justify-center gap-5">

        {#each cardCosts as item}
            <div class="w-80 h-80 rounded-2xl bg-amber-50 min-[500px]:hover:scale-110 duration-300 ease-out" style={item.card}>
                <div class="w-full h-full flex flex-col items-center justify-between">
                    <p class="bg-[#5c131ac2] p-1 text-center text-[24px] font-semibold  text-[white] transform translate-y-[20px] rounded-3xl">{item.name}</p>
                    <div class=""></div> <div class=""></div>
                  

                </div>
            </div>
            
        {/each}

    </div>


</section>