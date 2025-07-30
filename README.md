# vehicle-parking-system-v1

### About This Project

This is a simple Vehicle Parking Web App I made as a college project using Python, Flask, and SQLite. The purpose of the app is to help manage parking lots for four-wheelers and keep track of which users have parked where and when. There are two main types of users: **Admins** (who can add and manage parking lots and view all users), and **Normal Users** (who can register, book a parking spot, start parking, end parking, and see their history).

As an admin, you can create new parking lots, set how many spots they have, and control which lots are available. The system automatically creates the right number of parking spots for each lot. Admins can only delete parking lots if no spots are occupied. Both admins and users can search for parking lots by name or location, making it easy to find a suitable spot.

Normal users can register for an account, log in, search for lots, reserve parking spots by entering their vehicle number, and manage their bookings right from their dashboard. The system keeps track of both active and past reservations and shows users how much they spent. Users can also edit their profile information at any time.

The **database is managed automatically**: When you first run the app, it creates all the tables and a default admin user (`admin`/`admin123`), so there is no setup needed for the database. The web interface is made using Bootstrap and some custom CSS, making it easy to use on different devices.

Overall, the project gave me a good understanding of building a full-stack application with Flask and will make managing vehicle parking lots more streamlined!



