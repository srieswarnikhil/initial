# initial
Great repository names are short and memorable. Need inspiration? How about cautious-pancake ?

<html>
<head>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<script src="https://kit.fontawesome.com/3496c27bda.js" crossorigin="anonymous"></script>
<link rel="stylesheet" href="initial.css">
</head>
<body>
    
    <div class="first-part">
    <nav>
        <div class="logo">
            <img src="https://res.cloudinary.com/dndhjbuy4/image/upload/v1698649811/bjxzhknyjkhrv6k2p48l.svg" class="img-logo"/>
        </div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="./students.html">Students</a></li>
            <li><a href="./login.html">Employers</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
        <div class="three-bars-container">
            <i class="fa-solid fa-bars"></i>
        </div>
    </nav>
    <marquee behavior="scroll" direction="left" class="scrolling-text"> * Welcome to the AMPM JOBS Portal *</marquee>
    <div class="middle-part">
        <div class="first-obj order-2 order-md-1">
            <div class="some-image">
                <img src="https://res.cloudinary.com/dndhjbuy4/image/upload/v1701775264/wibyeyrian4ecrchuzhr.jpg" class="student-image"/>
            </div>
            <div class="some-content">
                <p class="some-para">Hello World,Welcome to the ampm jobs portal, Here more oppertunities and earn when you are in free time.
                    Who can join its above 18 years can join.How to register:Its very simple please select an option student if u are searching
                    for job and register.After completing registering process you are directly show jobs based on 5-Interests.Simple to follow 
                    Register,Apply,Selected,Earn Money.
                </p>
            </div>
        </div>
        <div class="first-obj order-3 order-md-2">
        <div class="some-content">
            <p class="some-para2">Hello World,Welcome to the ampm jobs portal, Here more oppertunities and earn when you are in free time.
                Who can join its above 18 years can join.How to register:Its very simple please select an option student if u are searching
                for job and register.After completing registering process you are directly show jobs based on 5-Interests.Simple to follow 
                Register,Apply,Selected,Earn Money.
            </p>
        </div>
        <div class="some-image">
            <img src="https://res.cloudinary.com/dndhjbuy4/image/upload/v1701503270/parrainage_i1ghfu.jpg" class="student-image"/>
        </div>
        </div>
        <div class="some-form order-1 order-md-3">
            <h1 class="login-form text-center">Select the options</h1>
            <br/>
            <form>
                <div class="input-container">
                <select>
                    <option>Choose an option</option>
                    <option>Students</option>
                    <option>Employers</option>
                    
                </select>
                <div class="text-end">
                <a href="./login.html">Clickhere to Login</a>
                </div>
                <br>
                <div class="text-center button-element">
                <a href ="./registrationpage.html" class="reg-ele">Create an Account</a>
            </div>
            </div>
            </form>
            
        </div>
    </div>
</div>

<script>
    function submitBtn(){
        alert("Hello World");
    }
</script>
<style>
    *{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
.three-bars-container{
    display: none;
}
@media screen and (max-width: 992px){

}
.img-logo{
    width: 300px;
    position: absolute;
    top: 20px;
}
nav{
    width: 100%;
    height: 10vh;
    line-height: 10vh;
    padding: 0px 10px; 
    position: relative;
    top: 0px;
    justify-content: space-between;
    background-color:#fdf7e4;

}
nav p{
    font-size: 30px;
    font-weight: bold;
    float: left;
    color: white;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    cursor: pointer;

}
nav ul{
    float: right;
}
nav li{
    display: inline-block;
    list-style-type: none;

}
nav li a{
    font-size: 18px;
    font-weight: bold;
    text-transform: uppercase;
    padding: 0px 30px;
    color: #000000;
    text-decoration: none;
}
nav li a:hover{
    color: #ff8c69;
    transition: all 0.4s ease 0s;
}
.scrolling-text{
    color: red;
}
.first-part{
    width: 100%;
    height: 100vh;
    position: relative;
    background-color:#fdf7e4;
}
.middle-part{
    height: 90vh;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 20px;
    width: 100%;

}
.student-image{
    width: 450px;
    height: 300px;
    
}
.some-image{
    width: 450px;
    margin: 20px;
}

.some-content{
    width: 450px;
    height: 300px;
    border: 1px solid transparent;
    background-color: transparent;
    margin: 20px;
    padding: 10px;
    justify-content: center;
    align-items: center;
    
}
.some-form{
    width: 300px;
    margin: 20px;
    float: right;
}
.login-form{
    font-size: 22px;
}
.some-para{
    color: #000000;
    font-size: 16px;
}
.some-para2{
    color: #000000;
    font-size: 16px;
    justify-content: end;
}
.para-password{
    color: blue;
}

.input-container{
    display: flex;
    flex-direction: column;
    width: 300px;
    border: 1px solid white;
    padding: 10px;

}
.reg-ele{
    text-decoration: none;
    padding: 10px;
    margin-bottom: 10px;
    color: white;
    background-color:green;
    border-color: green;
    border-radius: 10px;
    align-self: center;
    width: 100%;
    align-content: center;
}
.button-element{
    padding: 10px;
}
/* Existing CSS code remains unchanged */

@media screen and (max-width: 992px) {
    .img-logo {
        width: 200px; /* Adjust the logo size for smaller screens */
    }

    nav {
        height: auto;
        text-align: center;
        padding: 10px;
    }

    nav p {
        float: none;
        display: inline-block;
        margin: 0;
    }

    nav ul {
        float: none;
        display: block;
        margin-top: 10px;
    }

    nav li {
        display: block;
        text-align: center;
    }

    nav li a {
        padding: 10px;
        display: block;
    }

    .three-bars-container {
        display: block; /* Show the three-bars icon for mobile */
        float: right;
        cursor: pointer;
    }

    .first-part {
        height: auto;
    }

    .middle-part {
        flex-direction: column;
        align-items: center;
    }

    .some-image,
    .some-content,
    .some-form {
        width: 100%; /* Adjust width for smaller screens */
    }

    .student-image {
        width: 100%; /* Make the image responsive */
        height: auto;
    }

    .input-container {
        width: 100%; /* Adjust width for smaller screens */
    }
}

</style>
</body>    
</html>
