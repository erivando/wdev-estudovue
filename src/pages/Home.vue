<template>
  <main>
    <div class="text-top">
      Vídeos novos toda <b>quinta</b> às <b>20H</b>
    </div>

    <a href="https://youtube.com/wdevoficial" target="_blank">
      <img src=".././assets/subscribe.svg" alt="Inscreva-se" id="subscribe">
    </a>

    <div class="text-botton">
      youtube.com/wdevoficial
    </div>
  </main>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style scoped>
  main {
    background-color: var(--color-background-home);
    justify-content: center;
    align-items: center;
  }

  .text-top {
    color: var(--color-text-light);
    font-size: 22px;
    margin-bottom: 20px;
  }

  #subscribe {
    width: 340px;
  }

  .text-botton {
    color: var(--color-text-light);
    font-size: 18px;
    margin-top: 20px;
  }

  @media(min-width: 700px) {
    #subscribe {
      width: 370px;
    }
  }
</style>