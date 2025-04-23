# Ex.07 Restaurant Website
# Date: 20-04-2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
home.html
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="home.css">
</head>

<body>
    <div class="bg-cont">
        <div class="cont1 d-flex flex-row justify-content-center">
            <img src="https://img.freepik.com/free-photo/top-view-delicious-eggplant-rolls-with-potatoes-fresh-vegetables-dark-background-dish-dinner-ripe-meal-food_140725-116130.jpg?t=st=1745128513~exp=1745132113~hmac=866693b2f7d4f4d2ff0089b2d1c1946b65f491bbd95cd5fd6df8b4cb93023ae7&w=1380" class="image">
            <h1 class="mh">FOODIE</h1>
        </div>
        <div class="cont2 d-flex flex-row justify-content-between">
            <h2 class="mh2">Home</h2>
            <h2 class="mh2">menu</h2>
            <h2 class="mh2">Administration</h2>
            <h2 class="mh2">Contact us</h2>
        </div>
        <div class="cont3">
            <h1 class="mh3">30% off This weekend</h1>
            <p class="para1">Todays offers are more,and exiting free foods and 30% discount offer available in this week,location:vellore,vaduganthangal,e.b.colony,tamlinadu.all are come and enjoy to taste the delicious foods</p>
        </div>
        <div class="overall-cont456 d-flex flex-row">
            <div class="cont4 d-flex flex-column">
                <h2>Our New menu</h2>
                <img src="https://img.freepik.com/free-photo/view-delicious-dish-food_23-2150777655.jpg?t=st=1745130040~exp=1745133640~hmac=3d6cb96fa4c27e062ea140328f5193b07a5fd1cadf998db2ac330d0137ed0917&w=1380" class="image2">
                <p>Indulge in the rich aroma and irresistible flavors of our signature Biryani a timeless dish crafted with fragrant basmati rice, slow-cooked marinated meat or veggies, and a blend of authentic spices. Each spoonful is a celebration of tradition, taste, and love.</p>
            </div>
            <div class="cont5 d-flex flex-column">
                <h2>OFFER</h2>
                <img src="https://img.freepik.com/free-photo/delicious-food-table_23-2150857814.jpg?t=st=1745130354~exp=1745133954~hmac=93db52a7e13bf2fed21200de838638ed48a674f47cdf849dcd4f18817bdb83f6&w=1380" class="image2">
                <p>Ah, you want content for a meal combo or full meal plate that includes all meals at one fixed rate perfect for a set menu or thali concept. Here's some catchy and appetizing content for that:</p>
            </div>
            <div class="cont6 d-flex flex-column">
                <h2>Food Timing</h2>
                <img src="https://img.freepik.com/free-photo/hands-holding-knife-fork-alarm-clock-plate-blue-background_169016-21525.jpg?t=st=1745130548~exp=1745134148~hmac=e406e15a2b7d7cf38c560433b8d2a6504838e4ae3e07217956d5f0d0c386d424&w=1380" class="image2">
                <p>We serve delicious, freshly prepared meals every day from 10:00 AM to 4:00 PM, making it the perfect time for a hearty brunch, a fulfilling lunch, or a mid-day treat. During these hours, you can enjoy a variety of options including our popular All-in-One Meals, Biryani Specials, Roti & Curry Combos, and more</p>
            </div>
        </div>
        <h1 class="hari">Design and Developed by <span>Hariselvan S</span></h1>
    </div>
</body>

</html>

menu.html

<html>
    <head>
        <link rel="stylesheet" href="home3.css" />
    </head>
    <body>
        <div class="favourite-places-bg-container">
            <h1 class="favourite-places-heading">Food Menu</h1>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/premium-photo/yummy-chicken-pulao-isolated-white-background_787273-55616.jpg?w=826" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">Chicken Briyani</h1>
                    <p class="favourite-place-card-description">
                        Slow-cooked for deep flavor,100% fresh ingredients,served hot with raita & salan,A taste that keeps you coming back for more!
                    </p>
                    <p class="favourite-place-card-heading">Rs.150</p>
                </div>
            </div>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/free-photo/side-view-baked-chicken-with-cucumber-lemon-seasoning-bread-table_141793-4757.jpg?t=st=1745395710~exp=1745399310~hmac=40381ed561ed5f15e602e0f67c4051210165c86fb087f95987dbf21cb5545716&w=1380" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">Tandhoori</h1>
                    <p class="favourite-place-card-description">
                        Authentic spices & marinades,Cooked in a real clay tandoor oven,Juicy inside, crisp & smoky outside,Served with mint chutney, lemon wedges & love!
                    </p>
                    <p class="favourite-place-card-heading">Rs.400</p>
                </div>
            </div>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/free-photo/delicious-food-table_23-2150857814.jpg?t=st=1745396269~exp=1745399869~hmac=44ad66dab997101c343cd217be4fac161372300a1c216d248c287144cfe4d4b2&w=1380" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">veg meals</h1>
                    <p class="favourite-place-card-description">
                        Steamed Rice with Ghee,Sambar, Rasam & Kootu,Variety of Poriyals & Curries,Fresh Curd, Pickles & Papad,Sweet Payasam to end on a sweet note!
                    </p>
                    <p class="favourite-place-card-heading">Rs.100</p>
                </div>
            </div>

            <div class="favourite-place-card-container d-flex flex-row justify-content-center">
                <img src="https://img.freepik.com/premium-photo/idly-idli-south-indian-main-breakfast-item-which-is-beautifully-arranged-aqua-color-plates_527904-2880.jpg?w=1380" class="favourite-place-card-image" />
                <div>
                    <h1 class="favourite-place-card-heading">Idly</h1>
                    <p class="favourite-place-card-description">
                        Idly, made fresh daily with perfectly fermented batter and steamed to soft, cloud-like perfection.Spicy Sambar,Coconut & Tomato Chutneys,A dash of homemade love
                    </p>
                    <p class="favourite-place-card-heading">Rs.20</p>
                </div>
            </div>
        </div>
    </body>
</html>

contact.html

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="home2.css" />
</head>

<body>
    <section class="contact-section">
        <h2>Contact Us</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required />
            <input type="email" placeholder="Your Email" required />
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
</body>

</html>

admin.html

<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="home4.css">
    </head>
    <body>
        <div class="admin-container">
            <aside class="sidebar">
                <h2>Admin Panel</h2>
                <ul>
                    <li><a href="#">Dashboard</a></li>
                    <li><a href="#">Orders</a></li>
                    <li><a href="#">Users</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Settings</a></li>
                    <li><a href="#">Logout</a></li>
                </ul>
            </aside>
            <main class="main-content">
                <header>
                    <h1>Welcome, Admin</h1>
                </header>
                <section class="dashboard">
                    <div class="card">
                        <h3>Total Orders</h3>
                        <p>124</p>
                    </div>
                    <div class="card">
                        <h3>Total Users</h3>
                        <p>89</p>
                    </div>
                    <div class="card">
                        <h3>Revenue</h3>
                        <p>$2,350</p>
                    </div>
                </section>
            </main>
        </div>
    </body>
</html>


home.css

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.bg-cont {
    background-image: url("https://img.freepik.com/free-photo/slice-carrots-row-orange-background_23-2147927314.jpg?t=st=1745128315~exp=1745131915~hmac=81d063ff777a310327112cfd1c28afcbf203f13c6d0f2dfbbb9b4f1effd20c5f&w=740");
    background-size: cover;
}

.mh {
    color: white;
    font-weight: bold;
    font-size: 100px;
}

.image {
    height: 20%;
    width: 20%;
}

.cont1 {
    padding: 10px;
}

.cont2 {
    background-color: #00000080;
}

.mh2 {
    color: white;
    font-size: 20px;
    margin: 5px;
}

.cont3 {
    background-image: url("https://img.freepik.com/free-photo/view-ready-eat-delicious-meal-go_23-2151431768.jpg?t=st=1745129261~exp=1745132861~hmac=40a5aa3cae67e1c09802f26acbca3be06d943d4a6ddefaedde9f67051dfbba9d&w=1380");
    background-size: cover;
    padding: 10px;
    border-radius: 25px;
    margin: 8px;
}

.mh3 {
    color: white;
}

.para1 {
    color: white;
}

.image2 {
    height: 50%;
    width: 100%;
}

.cont4 {
    background-color: #fdedec;
    border-radius: 10px;
    padding: 10px;
    margin: 10px;
}

.cont5 {
    background-color: #fdedec;
    border-radius: 10px;
    padding: 10px;
    margin: 10px;
}

.cont6 {
    background-color: #fdedec;
    border-radius: 10px;
    padding: 10px;
    margin: 10px;
}

.hari {
    font-size: 20px;
    color: white;
    padding: 50px;
    text-align: center;
}

span {
    color: red;
}

.contact-section {
    background-color: rgba(255, 255, 255, 0.85);
    padding: 40px 20px;
    max-width: 600px;
    margin: 50px auto;
    border-radius: 15px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    text-align: center;
}

.contact-section h2 {
    margin-bottom: 20px;
    font-size: 2em;
    color: #004aad;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-form input,
.contact-form textarea {
    padding: 12px;
    font-size: 16px;
    border: 2px solid #004aad;
    border-radius: 10px;
    outline: none;
    transition: all 0.3s ease;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: #007bff;
    box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
}

.contact-form button {
    padding: 12px;
    font-size: 16px;
    background-color: #004aad;
    color: white;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    transition: background 0.3s ease;
}

.contact-form button:hover {
    background-color: #007bff;
}

.favourite-places-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
    height: 100vh;
    background-size: cover;
    background-attachment: fixed;
    overflow-y: auto;
}

.favourite-places-heading {
    color: #fff;
    font-size: 50px;
    font-weight: bold;
    padding: 24px;
    text-shadow: 0 0 5px #fff,
        0 0 10px #fff,
        0 0 20px #ff00ff,
        0 0 30px #ff00ff,
        0 0 40px #ff00ff,
        0 0 50px #ff00ff,
        0 0 60px #ff00ff;
    text-align: center;

}

.favourite-place-card-container {
    background-color: white;
    border-radius: 8px;
    padding: 16px;
    margin: 50px;
    background-attachment: fixed;
}

.favourite-place-card-heading {
    color: #0f0e46;
    font-family: "Roboto";
    font-size: 23px;
    font-weight: bold;
    text-align: center;
}

.favourite-place-card-description {
    color: #6c6b70;
    font-family: "Roboto";
    font-size: 13px;
    text-align: center;
}

.favourite-place-card-image {
    width: 80px;
    height: 100px;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background-color: #f0f2f5;
    display: flex;
}

.admin-container {
    display: flex;
    width: 100%;
}

.sidebar {
    width: 220px;
    background-color: #004aad;
    color: white;
    height: 100vh;
    padding: 20px;
    position: fixed;
}

.sidebar h2 {
    margin-bottom: 30px;
    font-size: 24px;
}

.sidebar ul {
    list-style: none;
}

.sidebar ul li {
    margin-bottom: 20px;
}

.sidebar ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

.sidebar ul li a:hover {
    text-decoration: underline;
}

.main-content {
    margin-left: 220px;
    padding: 20px;
    width: calc(100% - 220px);
}

header h1 {
    margin-bottom: 30px;
}

.dashboard {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background-color: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    width: 200px;
    text-align: center;
}

.card h3 {
    margin-bottom: 10px;
    color: #004aad;
}

.card p {
    font-size: 24px;
    font-weight: bold;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-04-20 121551.png>)

![alt text](<Screenshot 2025-04-20 121608.png>)

# menu page
![alt text](<Screenshot 2025-04-23 164834.png>)

# admin page
![alt text](<Screenshot 2025-04-23 164850.png>)

# contact page
![alt text](<Screenshot 2025-04-23 164905.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
