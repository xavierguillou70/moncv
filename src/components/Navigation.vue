<template>
  <div>
    <div id="home">
        
    </div>

    <ul class="navbar">
        <li class="h1">Xavier</li>
        <li>Experience</li>
        <li>Competences</li>
        <li>Blog</li>
        <li>Contact</li>
        <button class="button-download">CV Download</button>
    </ul>
  </div>
</template>

<script>

export default {
    name: 'Navigation',
}



</script>

<style scoped>

.h1, h1 {
    font-size: 30px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    justify-content: center;
    text-transform: uppercase;
    text-align: center;
    vertical-align: center;
}

li {
    
  
    margin: 10px;
    list-style-type: none;
    
}


.home {
    float: left;
    display: block;
    
}

.navbar {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    width: 100%;
    height: 100px;
}

.button-download {
    background: lightseagreen;
    color: lightyellow;
    border-style: none;
    border-radius: 5px;
    margin: 20px;
    vertical-align: middle;
    text-align: center;
}

</style>