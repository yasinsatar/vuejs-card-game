<template>
    <div class="card"> 
       </div>
</template>
<script>

</script>
<style scoped>
.card{
 width: 200px;
 height: 300px;
 border-radius: 20px;
 display: block;
 margin-top:10px;
 background-image:url('../assets/cards/card-secret.png');
 background-size: cover;
 background-repeat:no-repeat;
 background-position:center;
 box-shadow:0px 0px 30px rgb(75, 252, 243);
 cursor:pointer;
 object-fit:cover;
}

.card img{
   width:100%;
   border-radius: 5px;
}
@media screen and (max-width:768px){
.card{
    width: calc(35%);
    height:350px;
    flex-grow: 0;
    border:1px solid #AEAEAE;
    line-height: 0;
}
.card img{
    object-fit: cover;
}
}
@media screen and (max-width:568px){
.card{
    width: calc(35%);
    height:180px;
    flex-grow: 0;
    border:1px solid #AEAEAE;
    line-height: 0;
}
.card img{
    object-fit: cover;
}
}

</style>