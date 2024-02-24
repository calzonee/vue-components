<template>
    <button class="btn-grad">Planty Code</button>
</template>

<style scoped>
.btn-grad {
    background-image: linear-gradient(to right, #2ba32b 0%, #66ec45  51%, #32ad2d  100%);
    margin: 10px;
    padding: 15px 45px;
    text-align: center;
    text-transform: uppercase;
    transition: 0.5s;
    background-size: 200% auto;
    color: white;            
    box-shadow: 0 0 20px #81d66c;
    border: 0px solid #32ad2d;
    border-radius: 99px;
    display: block;
}

.btn-grad:hover {
    background-position: right center; /* change the direction of the change here */
    color: #fff;
    text-decoration: none;
}
         
</style>