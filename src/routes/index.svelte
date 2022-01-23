<script>

</script>

<svlete:head>
    <title>ma casa</title>
</svlete:head>

<body class="bg-gray-800 font-azert-mono">
    <div class="flex">
        <p class="text-slate-50 mt-24 ml-24 text-4xl font-azert-mono inline-flex">Hello BBG! </p> 
        <img src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/twitter/282/waving-hand_1f44b.png" alt="waving hand" class=" h-10 inline-flex mt-24 ml-4 wave">
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