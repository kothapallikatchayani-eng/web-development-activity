<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Yoga & Wellness Studio</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Serenity Yoga Studio</h1>
        <p>Find Your Inner Peace & Balance Daily</p>
        <hr>
        <!-- Navigation Links -->
        <nav>
            <a href="#about">About Us</a> |
            <a href="#classes">Classes</a> |
            <a href="#schedule">Schedule</a> |
            <a href="#join">Register</a>
        </nav>
        <hr>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Our Studio</h2>
        <p>Welcome to Serenity Yoga Studio! We provide a peaceful space for beginners and experienced practitioners to improve flexibility, strength, and mental wellness through guided yoga sessions.</p>
        <img src="https://images.unsplash.com/photo-1545205597-3d9d02c29597?auto=format&fit=crop&w=600&q=80" alt="Yoga Class Session" width="500">
    </section>

    <hr>

    <!-- Classes Section -->
    <section id="classes">
        <h2>Our Yoga Classes</h2>
        
        <h3>Hatha Yoga</h3>
        <p>A gentle introduction to basic yoga postures and breathing techniques. Perfect for beginners.</p>

        <h3>Vinyasa Flow</h3>
        <p>A dynamic class linking breath with continuous, fluid movement to build strength and endurance.</p>

        <h3>Pranayama & Meditation</h3>
        <p>Focused breathing exercises and guided meditation designed to reduce stress and enhance mindfulness.</p>
    </section>

    <hr>

    <!-- Class Schedule Section -->
    <section id="schedule">
        <h2>Weekly Class Schedule</h2>
        <table border="1" cellpadding="8">
            <thead>
                <tr>
                    <th>Class Name</th>
                    <th>Days</th>
                    <th>Timing</th>
                    <th>Level</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Hatha Yoga</td>
                    <td>Mon, Wed, Fri</td>
                    <td>06:30 AM - 07:30 AM</td>
                    <td>Beginner</td>
                </tr>
                <tr>
                    <td>Vinyasa Flow</td>
                    <td>Tue, Thu, Sat</td>
                    <td>07:00 AM - 08:00 AM</td>
                    <td>Intermediate</td>
                </tr>
                <tr>
                    <td>Pranayama & Meditation</td>
                    <td>Saturday & Sunday</td>
                    <td>05:00 PM - 06:00 PM</td>
                    <td>All Levels</td>
                </tr>
            </tbody>
        </table>
    </section>

    <hr>

    <!-- Registration Form Section -->
    <section id="join">
        <h2>Join a Class</h2>
        <form action="#" method="post">
            <label for="fullname">Full Name:</label><br>
            <input type="text" id="fullname" name="fullname" required><br><br>

            <label for="email">Email Address:</label><br>
            <input type="email" id="email" name="email" required><br><br>

            <label for="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone" required><br><br>

            <label for="class-select">Select Preferred Class:</label><br>
            <select id="class-select" name="class-select">
                <option value="hatha">Hatha Yoga</option>
                <option value="vinyasa">Vinyasa Flow</option>
                <option value="meditation">Pranayama & Meditation</option>
            </select><br><br>

            <label for="experience">Experience Level:</label><br>
            <input type="radio" id="beginner" name="experience" value="beginner" checked>
            <label for="beginner">Beginner</label>
            <input type="radio" id="intermediate" name="experience" value="intermediate">
            <label for="intermediate">Intermediate</label>
            <input type="radio" id="advanced" name="experience" value="advanced">
            <label for="advanced">Advanced</label><br><br>

            <input type="submit" value="Submit Registration">
        </form>
    </section>

    <hr>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2026 Serenity Yoga Studio. All Rights Reserved.</p>
        <p>Location: Peace Park Avenue, Wellness City</p>
    </footer>

</body>
</html>
