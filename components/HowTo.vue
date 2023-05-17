<template>
    <div class="pricing-table-2 bg-gray-800 py-6 md:py-12" id="example">
        <div class="max-w-3xl mx-auto text-center">
             <h1 class="text-3xl md:text-4xl font-medium text-white mb-4 md:mb-6">How to</h1>
        </div>
        <!--step1-->
        <PartHowToChild :step="1" :part="'Making the Patties for the Burger'" :desc="'Get the right meat. Get a butcher to grind chuck beef for you with a 20% fat content.[1] If you use more fat, it will just drip off the meat and cause fire flare-ups; less and the burgers will be dry.[2] If possible, buy the meat the day you’re going to cook it. Ask the butcher to grind the meat twice, once in the coarse plate of the grinder and then through the fine plate.'">
            <img class="w-full" src="https://www.wikihow.com/images/thumb/4/4e/Make-a-Hamburger-Step-1-Version-6.jpg/aid294606-v4-728px-Make-a-Hamburger-Step-1-Version-6.jpg.webp" alt="step1">
        </PartHowToChild>

         <!--step2-->
         <PartHowToChild :step="2" :part="''" :desc="'Place the ground beef in a bowl. You`ll add the other ingredients to it when you`re ready.'">
            <img class="w-full" src="https://www.wikihow.com/images/thumb/d/d6/Make-a-Hamburger-Step-2-Version-6.jpg/550px-nowatermark-Make-a-Hamburger-Step-2-Version-6.jpg.webp" alt="step2">
        </PartHowToChild>

         <!--step3-->
         <PartHowToChild :step="3" :part="''" :desc="'Roughly chop the onion and garlic. Put them in a bowl and mix them together until combined. Add any of the ingredients you want to add to the burger. This includes the Worcestershire sauce, ketchup, mustard, and the chopped herbs. These ingredients are optional, but they can add a special flavor to the meat.'">
            <img class="w-full" src="https://www.wikihow.com/images/thumb/3/3f/Make-a-Hamburger-Step-3-Version-6.jpg/550px-nowatermark-Make-a-Hamburger-Step-3-Version-6.jpg.webp" alt="step3"/>
        </PartHowToChild>
        
         <!--step4-->
         <PartHowToChild :step="4" :part="''" :desc="' Add the egg yolk. Season one egg yolk with salt and pepper and mix everything together.[3] It is easier to start mixing with a spoon; then use your clean hands to thoroughly combine the ingredients.'">
            <img class="w-full" src="https://www.wikihow.com/images/thumb/8/84/Make-a-Hamburger-Step-5-Version-6.jpg/550px-nowatermark-Make-a-Hamburger-Step-5-Version-6.jpg.webp" alt="step4">
        </PartHowToChild>

         <!--step5-->
         <PartHowToChild :step="5" :part="''" :desc="'Place the ground beef in a bowl. You`ll add the other ingredients to it when you`re ready.'">
            <img class="w-full" src="https://www.wikihow.com/images/thumb/a/af/Make-a-Hamburger-Step-6-Version-6.jpg/aid294606-v4-728px-Make-a-Hamburger-Step-6-Version-6.jpg.webp" alt="step5">
        </PartHowToChild>

        <PartHowTo></PartHowTo>
    </div>
</template>