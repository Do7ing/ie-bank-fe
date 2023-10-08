<template>
    <!-- Title -->
    <div><h1>Welcome to Zabri Bank</h1>
    
    <!-- Back ground image -->
    <body style="background-image: url('../assets/logo.png');"> </body>
    
    <!-- Service Button -->
    <div class="homepage">
        <div class="services">
            <div class="dropdown">
                <button class = "dropbtn">Services</button>
                <div class="dropcontent">
                    <router-link to="/accounts">Accounts</router-link>
                    <router-link to="/Skull">Skull</router-link>
                </div>
             </div>
        </div>
    </div>

    <!-- Logo -->
    <div class="logo">
        <img src="../assets/logo.png" alt="Logo"> 
    </div>

    <router-link></router-link>
    </div>

</template>


<!-- Css code -->
<script>
export default{
    name: 'Home',
    
};

</script>

<style scoped>
/* Title */
h1{
    z-index: 2;
    text-align: center;
    font-size: 50px;
    color: #4CAF50;
    font-family: Helvetica;
    position: relative;
}
/* Service Button */
.services{
    position: absolute;
    margin-left: -30px;
    left: 50%;
}

/* Logo */
.logo{
    position: absolute;
    top: 10px;
    right: 10px;
    z-index: 1;
}

/* Logo Image */
.logo img{
    width: 100px;
    height: 100px;
}

/* Dropdown Button Styling */
.dropbtn{
    background-color: #4CAF50;
    position: absolute;
    color: white;
    padding: 10px;
    font-size: 16px;
    border: none; 
    cursor: pointer;
}

.dropdown{
    position: relative;
    display: inline-block;
}

/* Dropdown Button Content */
.dropcontent {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
}

/* Dropdown Button Content Links */
.dropcontent a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    font-weight: bold;
}

/* Dropdown Button Content Hover */
.dropcontent a:hover {
    background-color: #ddd;
}

/* Show the dropdown menu on hover */
.dropdown:hover .dropcontent {
    display: block;
}

/* Home Page Image */
.homepage {
    background-image: url('@/assets/back.jpg'); /* Path to your background image */
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: rgb(48, 80, 142);
    font-family: Arial, sans-serif;
    text-align: center;
}


</style>


 
