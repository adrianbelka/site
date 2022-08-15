<template>
<div class="img-field">
<div class="img-src">
    <img src="../../public/images/sun.jpg" alt="" class="img-left">
</div>

<div class="img-title">
    <div img-blur>
        <img src="../../public/images/sun.jpg" alt="" class="img-blur">
    </div>
    <div class="title">
        <span>TITLE</span>
    </div>
</div>
</div>
</template>

<script>
export default {
  name: 'ImageField',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.img-field{
    width: 95%;
    height: 80vh;
    background-color: white;
    margin: auto;
    display: flex;
    justify-content: flex-start;
}
.img-src{
    background: grey;
    width: 60%;
    height: 100%;
}
.img-left{
    width: 100%;
    height: 100%;
}
.img-title{
    width: 40%;
    height: 100%;
    background-color: darkblue;
    display: flex;
    justify-content: center;
    align-content: end;
}
.img-blur{
    filter: blur(0.3rem);
    width: 100%;
    height: 100%;
    overflow: hidden;
}
.title{
    color: white;
    transform: rotate(90deg);
    font-size: 10rem;
    height: 50%;
    width: 50%;
    position: absolute;
}
</style>
