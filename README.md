# HOTEL MANAGEMENT SYSTEM

---

# Hotel Management System - The Royal Mansion 🏨

A comprehensive Python-based Hotel Management System designed to handle hotel operations efficiently. This program facilitates room bookings, restaurant services, payments, and record management with persistent data storage.

## Features

### 1. Room Booking
- Supports multiple room types:
  - **Standard Non-AC**: ₹3500
  - **Standard AC**: ₹4000
  - **3-Bed Non-AC**: ₹4500
  - **3-Bed AC**: ₹5000
- Automatically validates check-in and check-out dates.
- Assigns unique room numbers and customer IDs dynamically.
- Calculates the total cost based on room type and duration of stay.

### 2. Restaurant Services
- Displays an extensive menu with items and prices.
- Allows customers to order food and adds charges to their total bill.
- Generates a final restaurant bill along with room charges.

### 3. Payment Processing
- Supports multiple payment methods:
  - Credit/Debit Card
  - Paytm/PhonePe
  - UPI
  - Cash
- Ensures payments are processed only once to avoid duplicate transactions.

### 4. Hotel Records
- Maintains a record of all bookings.
- Displays customer details, check-in/check-out dates, room type, and charges.

### 5. Persistent Data Storage
- All data (customer details, bookings, and payments) is stored in a `customer_data.json` file for continuity.
- Automatically loads data when the program starts and saves updates.

### 6. User-Friendly Interface
- Simple text-based menu navigation.
- Clear prompts and messages to guide users through each operation.

---

## Installation and Usage

### Prerequisites
- Python 3.x installed on your system.

### Steps to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/hotel-management-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hotel-management-system
   ```
3. Run the script:
   ```bash
   python hotel_management.py
   ```

---

## How It Works
1. **Booking**: 
   - Enter customer details, check-in, and check-out dates.
   - Select a room type, and the system will calculate the total charges.
2. **Restaurant Services**: 
   - Place food orders using the menu.
   - The charges are added to the customer's room bill.
3. **Payment**: 
   - Choose a payment method and confirm the payment.
   - The system generates a detailed bill.
4. **Records**: 
   - View all past and current bookings and payment statuses.

---

## Future Enhancements
- Real-time room availability tracking.
- Graphical User Interface (GUI) for better user experience.
- Integration with online payment gateways.
- Multi-user support with role-based access control.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests for any improvements or additional features.

---

## Contact
For questions or suggestions, feel free to reach out:
- **Email**: rahultallart15@gmail.com
- **GitHub**: [rahultalla15](https://github.com/rahultalla15)

--- 
