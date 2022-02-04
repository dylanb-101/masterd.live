<script>
import Nav from "../components/nav.svelte"
</script>

<svlete:head>
    <title>ma casa</title>
</svlete:head>

<body class="bg-gray-800 font-azert-mono">
    <!--my hello and waving hand emoji-->
    <div class="flex">
        <p class="text-slate-50 mt-24 ml-24 text-4xl font-azert-mono inline-flex">Hello BBG! </p> 
        <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/twitter/282/waving-hand_1f44b.png" alt="waving hand" class=" h-10 inline-flex mt-24 ml-4 wave">
    </div>
    <!--intro paragraph-->
    <div class=" mt-14 ml-24 w-auto h-auto mr-16">
        <p class="text-slate-50 mr-16">This is my website pretty cool eh? I'm going to work on a bunch of games that I can host like Uno, cards, and other games that are annoying to play when your not with friends in real life. I'm also going to work on an admin page for my discord bot, and my rasberry pi so I can access all the files easily🥳. If you have any other things youd like to see me add let me know!</p>
    </div>

</body>



<style>
@import url('https://fonts.googleapis.com/css2?family=Azeret+Mono:wght@100&display=swap');
@tailwind base;
@tailwind components;
@tailwind utilities;


.wave {
  animation-name: wave-animation;  
  animation-duration: 2.5s;        
  animation-iteration-count: infinite;  
  transform-origin: 70% 70%;       
  display: inline-block;
}

@keyframes wave-animation {
    0% { transform: rotate( 0.0deg) }
   10% { transform: rotate(14.0deg) }  
   20% { transform: rotate(-8.0deg) }
   30% { transform: rotate(14.0deg) }
   40% { transform: rotate(-4.0deg) }
   50% { transform: rotate(10.0deg) }
   60% { transform: rotate( 0.0deg) } 
  100% { transform: rotate( 0.0deg) }
}
</style>