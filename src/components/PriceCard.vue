<template>
  <div class="card-container">
      <div class="price-header">
          <h2 class="price">{{data.price}}</h2>
          <p class="time">{{data.time}}</p>
      </div>

    <div class="plan-container">
        <div class="plan-name">
            <h2 class="plan">{{data.plan}}</h2>
        </div>

        <div class="plan-content">
            <p>lorem ipsum content</p>
            <p>lorem ipsum content</p>
            <p>lorem ipsum content</p>
            <p>lorem ipsum content</p>
        </div>
        <div class="button">
            <button>choose</button>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    props: {
        data:{
            type: Object
        }
    }
}
</script>

<style scoped>
/* prmiumcolor BE03fd */
/* Basic color 32bf84 */
/* ultimate 02066F */
.card-container{
    /* border: 2px solid red; */
    min-width: 350px;
    box-shadow: 3px 3px 3px 3px grey;
    border-radius: 10px;
}
.card-container:hover{
    z-index: 10px;

}
.price-header{
    padding: 20px;
}
.price{
    font-size: 45px;
    margin-bottom: 0;
    letter-spacing: 2px;
}
.plan-container{
    background-color: #BE03fd;
    color: white;
    padding: 3px;
    border-radius: 0 0 10px 10px;
}
</style>