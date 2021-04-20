<template>
  <div>
    <img class="centerdoge" alt="doge png" src="https://github.com/Lietsaki/Who-Is-Doge/blob/master/Images/Main%20Doge.png?raw=true">
  </div>
</template>

<style>
  @media only screen and (min-width: 600px) {
        .centerdoge {
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 35%;
          animation: float 3s ease-in-out infinite;
        }
  }

  @media only screen and (max-width: 600px) {
    .centerdoge {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
      animation: float 6s ease-in-out infinite;
    
    }
  }
</style>
