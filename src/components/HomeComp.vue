<template>
    <section class="slider position-relative">
        <div class="content position-absolute top-50 start-50 translate-middle">
        <h6>DESIGN / DEVELOPMENT / PHOTOGRAPHY</h6>
        <h1>CREATIVITY HAVE NEW LEVEL</h1>
        <a class="btn career me-4">PREVIEW</a>
        <a class="btn career">GET THEME</a>
        </div>
    </section>
</template>


<style>

.slider{
    background:url("../assets/imgs/header.jpg");
    background-size:cover;
    background-color:var(--second-color);
    background-blend-mode:multiply;
    height:85vh;
    color: var(--white)
}
.slider .content .career{
    color:var(--white);
    font-size:bold;
    border:1px solid 
}
.slider .content .career:hover{
    background-color:var(--main-color);
    border:1px solid var(--main-color)
}

</style>

<script>
export default{
    name :"slider"
}

</script>