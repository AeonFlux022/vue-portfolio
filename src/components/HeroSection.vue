<template>
    <div class="hero-section">
        <div class="hero-image">
            <img src="../assets/hero.png" />
        </div>
        <div class="hero-text">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Vel turpis nunc eget lorem dolor sed viverra ipsum nunc.</p>
            <br>
            <a href="#" class="button">LEARN MORE</a>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HeroSection',
    }
</script>

<style scoped>
.hero-section {
    /* max-width: 65em; */
    /* background-color: lightblue; */
    display:flex;
    flex-direction:row;
    justify-content:space-around;
}

.hero-image {
    display: flex;
    align-self: center;
    width: 50%;
    /* background-color: pink; */
    height: 500px;
}
.hero-image img {
    display: inline-flex;
    height: inherit;
    width: auto;
}
.hero-text {
    align-self: center;
    padding: 0 50px;
    /* background-color: yellow; */
    width: 50%;
}
.hero-text .button {
    transition: 0.4s;
    text-decoration: none;
    color: #fff;
    padding: 15px 30px;
    background-color: #EF8354;
}
.hero-text .button:hover {
    background-color: #fff;
    border: 1px solid #EF8354;
    color: #EF8354;
}

</style>