# City Metro

City Metro is a comprehensive web application designed to facilitate metro travel for users. The app includes features such as a dashboard, ticket booking, ticket history, QR code for tickets, Razorpay payment integration, and more. The backend is written in PHP and uses a MySQL database.

## Features

### Dashboard
- Provides an overview of the metro services.

### Ticket and Monthly Pass Booking
- Allows users to book metro tickets and monthly passes.
- Easy and intuitive booking process.

### Ticket History
- Keeps a record of all the tickets and passes booked by the user.
- Provides details such as date of booking, amount, and validity.

### QR Code for Tickets
- Generates a QR code for each booked ticket.
- Users can scan the QR code at metro stations for easy access.

### Razorpay Payment Integration
- Secure and seamless payment processing using Razorpay.
- Supports multiple payment methods.


### MySQL Database
- Uses MySQL database to store and manage user data, booking information, and transaction details.

## Installation and Running the Application

### Prerequisites
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Composer
- Node.js and npm (for frontend dependencies)
  
### Backend Setup

1. **Clone the Repository**
   ```bash
   ```](https://github.com/gokuldeore21/City-Metro)
   


3. **Set Up the Database**
   - Create a MySQL database.
   - Import the provided SQL file to set up the database schema.
     ```bash
     mysql -u your-username -p your-database-name < database/schema.sql
     ```

4. **Configure the Database**
   - Copy the `.env.example` file to `.env` and update the database credentials.
     ```bash
     cp .env.example .env
     ```
   - Update the `.env` file with your database settings:
     ```env
     DB_HOST=your-db-host
     DB_PORT=your-db-port
     DB_DATABASE=your-db-name
     DB_USERNAME=your-db-username
     DB_PASSWORD=your-db-password
     ```

5. **Start the Backend Server**
   ```bash
   php -S localhost:8000 -t public
   ```


### Running the Application
3. Open your web browser and navigate to:
   ```url
   http://localhost:3000
   ```

## Contributing

Contributions are welcome!


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
