<script lang="ts">

    let cardCosts = [
       
        {name: "Heavy fertilizer usage", img: "icons/heavy.webp", width: "250px", style: "rounded-[18px]",  card: "background: url('icons/heavy.webp') no-repeat;background-size: cover;"},
        {name: "Loss of flavour & smell", img: "icons/old.webp", width: "275px", style: "rounded-[18px]", card: "background: url('icons/old.webp') no-repeat;background-size: cover;"},
        {name: "More moisture, less oil ", img: "icons/water.webp", width: "250px", style: "rounded-[18px]", card: "background: url('icons/water.webp') no-repeat;background-size: cover;"},

    ]

</script>

<header class="min-md:pb-[20px]" style="background: rgb(228, 220, 201);">
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


<section class="bg-[#441f1f] pt-[20px] pb-7">
    <div class="h-[20px] w-full"></div>
    <h2 class="text-center text-white" style="text-transform: capitalize;">Drawback of purchasing cinnamon in markets</h2>
    <br>

    <div class="flex flex-row flex-wrap justify-center gap-5">

        {#each cardCosts as item}
            <div class="w-80 h-80 rounded-2xl bg-amber-50 min-[500px]:hover:scale-110 duration-300 ease-out" style={item.card}>
                <div class="w-full h-full flex flex-col items-center justify-between">
                    <p  style="color: rgb(228, 220, 201);" class="bg-[#5c131ac2] p-1 text-center text-[18px]  transform translate-y-[20px] rounded-3xl">{item.name}</p>
                    <div class=""></div> <div class=""></div>
                  

                </div>
            </div>
            
        {/each}

    </div>
    <br><br>

    <p class="text-center text-white mb-[3px] transform translate-x-[0px]">Traditional market quality of cinnamon</p>

    <div class="flex justify-center gap-[20px]">
        <div class="w-[7px]"></div>
        <div class="w-[300px] h-[20px] bg-[#dce4c9] rounded-2xl">
            <div class={"h-full border border-1 border-[#dce4c9] w-[54%] rounded-2xl bg-amber-500 min-[500px]:hover:bg-amber-900  hover:duration-500 "} ></div>
        </div>
        <p class="text-white transform translate-y-[-2px]">54%</p>
    </div>

    <br>

    <p class="text-center text-white mb-[3px]">Quality of our D&D Ceylon Cinnamon</p>

    <div class="flex justify-center gap-[20px]">
        <div class="w-[7px]"></div>
        <div class="w-[300px] h-[20px] bg-[#dce4c9] rounded-2xl">
            <div class={"h-full border border-1 border-[#dce4c9]  rounded-2xl  bg-green-400 min-[500px]:hover:bg-amber-900 hover:duration-500 " + " w-[97%]"} ></div>
        </div>
        <p class="text-white transform translate-y-[-2px]">97%</p>
    </div>

    <br><br>

    <p class="text-center  mb-[6px] text-[29px] text-[#dce4c9] font-semibold">What some other vendors sell as Ceylon Cinnamon ?</p>

    <div class="overflow-hidden min-[618px]:rounded-2xl max-w-[600px] mx-auto">
        <img class="mx-auto  min-[618px]:rounded-2xl max-[622px]:w-[100%] w-[600px] transform hover:scale-102 duration-300" src="images/war.webp" alt="cassia">
    </div>
    <p class="text-center  mb-[3px]  text-[#dce4c9]  m-3 translate-y-[-12px]">"Cassia Cinnamon" is Chinese cinnamon. <br class="min-[500px]:hidden"> Fake cinnamon.</p>






</section>

<section style="background: rgb(228, 220, 201);">
    <h1>Hello</h1>
</section>