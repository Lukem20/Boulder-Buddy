
<h1 class="gradient-text"><span>Boulder Buddy,</span> an outdoor climbing guide.</h1>

<style>

  .gradient-text {
    background: linear-gradient(to right, #FF9000,#BFB074,#EAE482);
    background-size: 200% 200%;
    animation: rainbow 2s ease-in-out infinite;
    -webkit-background-clip:text;
    width:80vw;
    margin:10vh auto;
    transition: color .2s ease-in-out;
    text-transform:uppercase;
    font-weight:900;

  }

  .gradient-text:hover {
    color:rgba(0,0,0,0);
  }


  @keyframes rainbow { 
    0%{background-position:left}
    50%{background-position:right}
    100%{background-position:left}
  }

</style>