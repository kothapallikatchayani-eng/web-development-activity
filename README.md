<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Spice Villa Restaurant</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Spice Villa</h1>
        <p>Delicious & Fresh Food Daily</p>
        <hr>
        <!-- Navigation Links -->
        <nav>
            <a href="#about">About Us</a> |
            <a href="#menu">Menu</a> |
            <a href="#timings">Timings</a> |
            <a href="#contact">Contact Us</a>
        </nav>
        <hr>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Our Restaurant</h2>
        <p>Welcome to Spice Villa! We serve authentic and delicious meals made with fresh ingredients. Founded in 2024, our goal is to bring great taste and quality service to our customers.</p>
        <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=600&q=80" alt="Restaurant Interior" width="500">
    </section>

    <hr>

    <!-- Menu Section -->
    <section id="menu">
        <h2>Our Menu</h2>
        
        <h3>Starters</h3>
        <ul>
            <li>Paneer Tikka - ₹220</li>
            <li>Chicken Wings - ₹260</li>
            <li>Veg Spring Rolls - ₹180</li>
        </ul>

        <h3>Main Course</h3>
        <ul>
            <li>Butter Chicken - ₹340</li>
            <li>Dal Makhani - ₹240</li>
            <li>Veg Biryani - ₹220</li>
            <li>Garlic Naan - ₹50</li>
        </ul>

        <h3>Desserts & Drinks</h3>
        <ul>
            <li>Gulab Jamun - ₹90</li>
            <li>Vanilla Ice Cream - ₹80</li>
            <li>Fresh Lime Soda - ₹60</li>
        </ul>
    </section>

    <hr>

    <!-- Timings Section -->
    <section id="timings">
        <h2>Opening Hours</h2>
        <table border="1" cellpadding="8">
            <thead>
                <tr>
                    <th>Day</th>
                    <th>Opening Time</th>
                    <th>Closing Time</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Monday - Friday</td>
                    <td>11:00 AM</td>
                    <td>10:00 PM</td>
                </tr>
                <tr>
                    <td>Saturday - Sunday</td>
                    <td>11:00 AM</td>
                    <td>11:00 PM</td>
                </tr>
            </tbody>
        </table>
    </section>

    <hr>

    <!-- Contact & Reservation Form -->
    <section id="contact">
        <h2>Reserve a Table</h2>
        <form action="#" method="post">
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>

            <label for="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone" required><br><br>

            <label for="guests">Number of Guests:</label><br>
            <input type="number" id="guests" name="guests" min="1" max="10" required><br><br>

            <label for="date">Date:</label><br>
            <input type="date" id="date" name="date" required><br><br>

            <label for="notes">Special Requests:</label><br>
            <textarea id="notes" name="notes" rows="4" cols="30"></textarea><br><br>

            <input type="submit" value="Book Now">
        </form>
    </section>

    <hr>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2026 Spice Villa. All Rights Reserved.</p>
        <p>Location: Main Street, City Center</p>
    </footer>

</body>
</html>
