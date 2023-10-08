<template>
    <!-- Title -->
    <div><h1>Welcome to Zabri Bank</h1>
    
    <!-- Service Button -->
    <div class="homepage" style="background-image: url('../assets/backgroundimg.jpg');
">
        <div class="services">
            <button class = "dropbtn">Services</button>
            <div class="dropdown-content">
                </div>
            </div>
        </div>

    <!-- Logo -->
    <div class="logo">
        <img src="../assets/logo.png" alt="Logo"> <!-- Add image -->
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

.services{
    position: absolute;
    top: 10px;
    left: 10px;
    z-index: 1;
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
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none; 
}

/* Dropdown Button Content */
.dropbtncontent{
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}

/* Home Page Image */
.homepage{
    background-image: url("../assets/backgroundimg.jpg");
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
}


</style>


 
