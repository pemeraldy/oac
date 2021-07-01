<template>
    <form class="form news-letter d-flex position-relative">
        <input class="w-100" type="text" placeholder="Email address">
        <button class="btn bg-sec position-absolute">Submit</button>
    </form>
</template>

<script>
export default {

}
</script>

<style>
.news-letter {
    width: 671px;
    height: 80px;
    border-radius: 90px;
    background: #fff;
    padding-left: 30px;
}
.news-letter input{
    border: 0;
    background: transparent;    
    outline: 0;
}
.news-letter button:hover{
    color: rgb(241, 239, 239);
}
.news-letter button{
    color: #fff;
    background: #000;
    height: 60px;
    width:150px;
    border-radius: 90px;
    top: 13%;
    right: 10px;
    text-transform: uppercase;
}

/* Responsive */
@media screen and (max-width: 500px) {
    .news-letter{
        height: 60px;
    }
    .news-letter button{
        height: 44px;
        width: 100px;
    }
}
</style>