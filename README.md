# Car Rental System in Java

A simple Car Rental System implemented in Java that allows users to rent cars, manage bookings, and handle customer data efficiently. This project is designed for understanding core Java concepts, object-oriented programming (OOP), and basic file handling.

---

## Features

- **Add, view, update, and delete car details**
- **Manage customer records**
- **Book cars for rental**
- **Calculate rental costs**
- **Display available cars**
- **Save and retrieve data using file storage**

---

## Project Structure

```
CarRentalSystem/
├── src/
│   ├── Car.java
│   ├── Customer.java
│   ├── Booking.java
│   ├── Main.java
└── README.md
```

### Class Descriptions

1. **Car.java**

   - Represents the car entity with attributes like car ID, model, brand, rental price, and availability status.

2. **Customer.java**

   - Manages customer information such as customer ID, name, contact details, and address.

3. **Booking.java**

   - Handles car rental bookings, including booking ID, customer details, car details, rental period, and total cost.

4. **Main.java**

   - The entry point of the application, providing a console-based menu to interact with the system.

---

## Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/car-rental-system.git
   cd car-rental-system
   ```

2. **Compile the Java Files**

   ```bash
   javac src/*.java
   ```

3. **Run the Program**

   ```bash
   java src/Main
   ```

---

## Sample Usage

1. **Add a Car**

   ```plaintext
   Enter Car ID: C001
   Enter Model: Toyota Camry
   Enter Brand: Toyota
   Enter Rental Price: 50
   Car added successfully!
   ```

2. **Book a Car**

   ```plaintext
   Enter Customer ID: CU123
   Enter Car ID to Rent: C001
   Enter Rental Period (days): 5
   Booking Confirmed. Total Cost: $250
   ```

---

## Technologies Used

- **Java**
- **File Handling** (for data persistence)

---

## How to Contribute

1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a Pull Request.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## Contact

**Aayush Sinha**\
Email: aayush.10sinha\@example.com\
GitHub: sinhaaayush10

