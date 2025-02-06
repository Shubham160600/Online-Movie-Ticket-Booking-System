# Online Movie Ticket Booking System

## Overview
The Online Movie Ticket Booking System is a web application designed to allow users to book movie tickets online. The system provides an easy-to-use interface for users to browse available movies, select their preferred showtimes, and complete the booking process seamlessly.

## Features
### User Registration and Authentication
- Users can register on the platform with their details like name, email, and password.
- Secure user authentication using PHP sessions and MySQL database.

### Movie Listings
- Display a list of movies currently playing in theaters.
- Each movie listing includes details such as title, genre, release date, and poster image.

### Theater Selection
- Allow users to select their preferred theater based on location or movie preference.
- Provide information about each theater, including address, contact details, and available facilities.

### Showtime Selection
- Display available showtimes for selected movies at chosen theaters.
- Show relevant details like date, time, available seats, and ticket prices.

## Technologies Used
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Backend: PHP
- Database: MySQL

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/Shubham160600/Online-Movie-Ticket-Booking-System.git
   ```
2. Set up a local development environment:
   - Install XAMPP or any other local server that supports PHP and MySQL.
   - Start the Apache and MySQL services.

3. Import the database:
   - Create a new database in phpMyAdmin.
   - Import the `movie_ticket_booking.sql` file into the newly created database.

4. Configure the database connection:
   - Open the `config.php` file and update the database credentials with your own.

5. Start the application:
   - Place the project files in the `htdocs` directory of your local server.
   - Access the application by navigating to `http://localhost/Online%20Movie%20Ticket%20Booking` in your browser.

## Usage
1. Register or log in to your account.
2. Browse the available movies and select a movie you want to watch.
3. Choose a theater from the list of available theaters.
4. Select a showtime and proceed to seat selection.
5. Complete the booking process by entering payment details and confirming the purchase.

## Contributing
Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Feel free to customize the README.md file further based on the specific details and requirements of your project.
