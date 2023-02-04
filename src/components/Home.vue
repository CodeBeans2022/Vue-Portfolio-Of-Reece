<template>
    <div class="container-fluid">
        <section class="homeSection">
            <h1 class="lead mb-3">Portfolio Of Reece Simon</h1>
            <div class="container px-0 ">
                <button class="proceedBtn btn"><a href="/about" style="text-decoration: none; color: #a7bcb9;">Have a Look!</a></button>
                <a href="tel:" class="customLink ms-3">Call: 067 743 2579</a>
            </div>
        </section>
    </div>
</template>

<script>
export default{}
</script>

<style scoped>
.container-fluid{
    min-height: 100vh;
    background: url('https://i.postimg.cc/GmqCptZq/Rhome.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    box-shadow: 2.5px 7.5px 5px 1px #000;

}   
.homeSection{
  border-radius: 1rem;
  padding: 0.5em;
}
.homeSection h1{
    font-size: 4em;
    color: #a7bcb9;
    font-weight: bold;
    text-shadow: 2.5px 5px 5px #000;
}
.customLink{
    font-weight: bold;
    position: relative;
    text-decoration: none;
    
    color: #a7bcb9;
}

.proceedBtn{
    color: #a7bcb9;
    font-weight: bold;
    border: 1px solid #a7bcb9;
}
.proceedBtn:hover{
    color:white;
    border: 1px solid #a7bcb9;
    background-color: rgb(124, 19, 19);

}
.customLink::after{
    content: "";
    position: absolute;
    width: 0%;
    height: 2px;
    left: 0;
    top: 110%;
    transition: all 0.5s ease;
    background-color: #a7bcb9;
}

.customLink:hover::after{
    width: 100%;
}

</style>