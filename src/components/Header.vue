<script setup>

</script>

<template>
      <header> 
        <h1>NotFlix</h1>
    </header>

    <nav>
        <button>Log In</button>
        <button>Register</button>
    </nav>
</template>


<script setup>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: #141414;
    color: #fff;
    line-height: 1.6;
}

header {
    background-color: #e50914;
    padding: 10px 20px;
    text-align: center;
}

header h1 {
    font-size: 3rem;
    color: #000000;
}

nav {
    display: flex;
    justify-content: flex-end;
    padding: 10px 20px;
}

nav button {
    background-color: #e50914;
    color: #fff;
    border: none;
    padding: 10px 20px;
    margin: 5px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 4px;
}

nav button:hover {
    background-color: #f40612;
}


.hero {
    text-align: center;
    padding: 20px 20px;
    background-image: url('hero-background.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
}

.hero h2 {
    font-size: 2.5rem;
    margin-top: -20px;
}

.hero p {
    font-size: 1.2rem;
}

.features {
    padding: 20px;
    background-color: #222;
    text-align: center;
}

.features h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.anime {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.anime img {
    width: 200px;
    height: auto;
    border-radius: 10px;
    transition: transform 0.3s;
}

.anime img:hover {
    transform: scale(1.05);
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #141414;
    color: #777;
}

footer p {
    font-size: 0.9rem;
    
}
</script>