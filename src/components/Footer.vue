<template>
    <div>
        <h1>Densenvolvimento de aplicacoes web @BeneditoMuianga</h1>
    </div>
</template>


<script>
    export default {
        name:'rodape',
    }
</script>

<style scoped>
  div{
    width: 100%;
    position: fixed;
    bottom: 0;
    background-color: #3c1c6628;
  }
  h1{
   
    padding-top: 5px;
    text-align: center;
    font-size: 17px;
  }

  @media only screen and (max-width: 900px) {
    div{
      margin-top: 20px;
      position:relative;
      margin-bottom: -10px;
    }
  }

  @media only screen and (max-width: 750px) {
    h1{color:white}
  }
</style>