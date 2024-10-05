# Go Conference Ticket Booking System 🎟️

## 🚀 Project Overview

This is a **Go-based application** for booking tickets to a conference. The application allows users to:
- Register for a conference by providing their name, email, and number of tickets.
- Check available tickets in real-time.
- Receive their ticket details via email simulation after a successful booking.

The system uses **Go’s goroutines** for concurrent ticket sending, improving the speed of the ticket delivery process.

## 📚 Features

- **Ticket Booking**: Book multiple tickets with input validation.
- **Concurrent Ticket Delivery**: Simulated email delivery using goroutines for efficient ticket processing.
- **User Input Validation**: Ensures valid names, emails, and ticket numbers.
- **Live Availability Updates**: Displays remaining tickets in real-time as users make bookings.

## 🛠️ Tech Stack

- **Go**: The main programming language.
- **Sync Package**: Manages concurrency using `sync.WaitGroup`.
- **Helper Functions**: External helper functions for input validation.

## ⚡ Quick Start

### Prerequisites:
- **Go (v1.16 or later)** installed on your system.

### Running the Project:

1. Clone the repository:
    ```bash
    git clone https://github.com/Ujjawal0902/ticket-booking-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ticket-booking-app
    ```

3. Run the application:
    ```bash
    go run main.go
    ```

4. Follow the prompts to book your tickets!

### Sample Interaction:

```bash
Welcome to the Go Conference booking application
We have a total of 50 tickets, and 50 are still available.
Get your tickets here to attend
Enter your first name: John
Enter your last name: Doe
Enter your email: john.doe@example.com
Enter number of tickets: 2
Thank you John Doe for booking 2 tickets. You will receive a confirmation email at john.doe@example.com
48 tickets remaining for Go Conference
