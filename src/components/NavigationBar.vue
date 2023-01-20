<template>
    <div class="navbar">
        <div className="logo"><a href="#">Kevin Tolentino</a></div>
            <div className="buttons">
                <ul>
                <a href="#"><li>Home</li></a>
                <a href="#"><li>Skills</li></a>
                <a href="#"><li>Portfolio</li></a>
                <a href="#"><li>Contact Us</li></a>
                </ul>
            </div>
    </div>
</template>

<script>
    export default {
        name: 'NavigationBar'
    }

</script>

<style scoped>
/*.navbar {
    background-color: yellow;
    display: grid;
    grid-template-columns: minmax(repeat(1fr));
    grid-template-rows: minmax(repeat(1fr, 1fr));;
    grid-template-areas:
    ". list .";
}
.navbar ul li {
    grid-area:list;
    background-color:orange;
    display:inline-flex;
    flex-direction:row;
}*/
.buttons {
    display:flex;
    width:45%;
    justify-content:flex-end;
}
.navbar {
    display:flex;
    flex-direction:row;
    justify-content:space-around;
    background-color:#2D3142;
    /* space-between ; end to end */
    /* space-around : margin from both ends */
}
.navbar a {
    text-decoration: none;
}
 .navbar ul li{
    transition: 0.4s;
    text-decoration: none;
    list-style: none;
    flex-direction: row;
    display: inline-flex;
    padding: 15px 18px;
    margin: 0 5px;
    color: #fff;
}
.navbar ul li:hover {
    background-color: #EF8354; 
}
.logo {
    display:flex;
    align-self:center;
    /* background-color:orange; */
    width:45%;
    color: #fff;
    justify-content:flex-start;
}
.logo a {
    text-decoration: none;
    color:#fff;
    padding: 15px 0;
    margin: 0 5px;
}


</style>