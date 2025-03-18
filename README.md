🌟 University Events Website
🚀 A centralized platform to manage and explore university events seamlessly!

📌 Description
The University Events Website is a user-friendly platform designed to keep students, faculty, and staff informed about upcoming university events. Whether it’s hackathons, cultural fests, seminars, or workshops, this website provides a structured way to explore events, check details, and register easily.

This project is built using HTML & CSS, featuring a clean, modern, and responsive design. The website allows users to:
✅ Browse upcoming events 📅
✅ View event details 📝
✅ Register with a single click 🎟️


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>University Events Website</title>
    <style>
        /* General Page Styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f9fa;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* Header Styling */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            font-size: 28px;
            font-weight: bold;
        }

        /* Main Content Section */
        .container {
            width: 80%;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.1);
        }

        /* Headings */
        h2 {
            color: #3498db;
        }

        /* Paragraph Styling */
        p {
            font-size: 16px;
            line-height: 1.6;
        }

        /* Event Section Styling */
        .event-list {
            text-align: left;
            margin-top: 20px;
        }

        .event {
            background: #ecf0f1;
            padding: 15px;
            margin: 10px 0;
            border-radius: 5px;
        }

        /* Footer */
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>🎉 Welcome to the University Events Hub</header>

    <!-- Main Container -->
    <div class="container">
        <!-- Introduction -->
        <h2>About the University Events Website</h2>
        <p>
            The University Events Website is a platform designed to keep students and faculty updated 
            about upcoming events at the university. From academic seminars to cultural festivals, 
            this website serves as a one-stop destination for all event-related information.
        </p>
        <p>
            Whether you're interested in hackathons, guest lectures, or sports competitions, 
            this platform ensures you never miss an important event. Students can explore event 
            details, register for participation, and stay connected with the university community.
        </p>

        <!-- Event Listings -->
        <h2>📅 Upcoming Events</h2>
        <div class="event-list">
            <div class="event">
                <h3>🚀 Hackathon 2025</h3>
                <p><strong>Date:</strong> April 10, 2025</p>
                <p><strong>Venue:</strong> Computer Science Auditorium</p>
                <p><strong>Description:</strong> A 24-hour coding challenge where students form teams and compete 
                    to develop innovative tech solutions.</p>
            </div>

            <div class="event">
                <h3>🎭 Cultural Fest 2025</h3>
                <p><strong>Date:</strong> May 5-7, 2025</p>
                <p><strong>Venue:</strong> University Amphitheater</p>
                <p><strong>Description:</strong> A three-day festival with music, dance, and drama performances 
                    featuring students and special guests.</p>
            </div>

            <div class="event">
                <h3>📢 AI & ML Seminar</h3>
                <p><strong>Date:</strong> March 25, 2025</p>
                <p><strong>Venue:</strong> Innovation Hub</p>
                <p><strong>Description:</strong> A seminar discussing the latest trends in Artificial Intelligence 
                    and Machine Learning, hosted by industry experts.</p>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>📩 Contact Us: events@university.com | 📍 Location: University Campus</footer>

</body>
</html>
