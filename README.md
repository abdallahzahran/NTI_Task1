# Theater Booking System (Dart)

## Description
This is a simple command-line-based theater booking system implemented in Dart. It allows users to book seats, check seat availability, and display booking details.

## Features
- **Book a Seat:** Users can select a seat by providing their name and phone number.
- **Check Theater Seats:** Displays the current seating arrangement (5x5 grid with 'E' for empty and 'B' for booked seats).
- **View Booking Details:** Shows all booked seats along with user details.
- **Exit:** Allows the user to exit the program.

## How It Works
1. Run the script.
2. Choose an option from the menu:
   - `1` to book a new seat
   - `2` to show the theater seats
   - `3` to show user booking details
   - `4` to exit
3. Follow the prompts to enter seat position, name, and phone number when booking.
4. The system updates the seating layout and booking records accordingly.

## Example Run
```
Welcome To Our Theater

press 1 to book new seat
press 2 to show the theater seats
press 3 to show users data
press 4 to exit
input=>2
Theater Seats:
E E E E E
E E E E E
E E E E E
E E E E E
E E E E E

press 1 to book new seat
press 2 to show the theater seats
press 3 to show users data
press 4 to exit
input=>1
Enter row (1-5):
input=>3
Enter column (1-5):
input=>4
Enter your name:
input=>Ahmed
Enter your phone number:
input=>010456755555
Seat booked successfully!
```

## Requirements
- Dart SDK installed

## How to Run
1. Save the script as `theater_booking.dart`.
2. Open a terminal and navigate to the script location.
3. Run the script using:
   ```
   dart run theater_booking.dart
   ```
4. Follow the on-screen instructions.

## License
This project is open-source and free to use.

## Author
Developed by Abdullah Zahran

