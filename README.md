🎬 Cinema Ticket Booking & Management System (Python)

📌 Overview  
This is a console-based Cinema Ticket Booking and Management System written in Python.  
It simulates a real-world cinema environment with multiple user roles, including **customers, cinema managers, technicians, and ticketing clerks**.

- The `Code` folder contains the Python source file along with text files used in the program (with sample data).  
- The `Documentation` file provides function-by-function explanations along with sample test runs.  

The system supports:  
- Movie listings  
- Ticket booking & seat selection  
- Payments (card, online banking, e-wallet, cash)  
- Food ordering  
- Booking cancellation & refunds  
- Technical issue reporting  
- Rewards & penalties  
- Feedback collection  
- Overall reporting  

All data is stored using text files to keep the project simple and beginner-friendly.

---

🧑‍💼 User Roles & Features  

👤 **Customer**  
- Register & Login  
- View available movies by date  
- Book cinema tickets  
- Select seats via seat layout  
- Apply discount codes  
- Order food online  
- Make payments  
- View booking history  
- Cancel bookings (with refund handling)  
- Report technical issues  
- Submit feedback  

🎟 **Ticketing Clerk (Hidden Access)**  
- Handle cash payments  
- Book tickets for walk-in customers  
- Process food orders  
- Manage food collection  

🛠 **Technician (Hidden Access)**  
- View reported technical issues  
- Update issue status (Fixed / No Issue)  
- Issue rewards or penalties based on reports  

🎥 **Cinema Manager (Hidden Access)**  
- Add movie listings  
- Update movie listings  
- Remove movie listings  
- View overall reports  
- View customer feedback  

---

💳 Payment Methods Supported  
- Card  
- Online Banking  
- E-Wallet  
- Cash (in-store)  

Refunds are handled automatically upon booking cancellation.

---

🍿 Food Ordering  
- Popcorn (Regular / Large)  
- Combo meals  
- Drinks  

Supports both online and in-store food ordering, with food collection tracking.

---

🏷 Discount & Reward System  
- Discount codes (H, M, L)  
- Rewards for valid technical issue reports  
- Penalties for repeated false reports  

---

📁 Files Used (Persistent Storage)  

| File Name          | Purpose                |
|--------------------|------------------------|
| Show Timings.txt   | Movie listings         |
| Users.txt          | Registered users       |
| Bookings.txt       | Ticket bookings        |
| Payment.txt        | Online payments        |
| Cash Payment.txt   | Cash payments          |
| Seats.txt          | Seat layout per show   |
| Food.txt           | Food orders            |
| Rewards.txt        | Rewards & penalties    |
| Issues.txt         | Technical issues       |
| Feedback.txt       | Customer feedback      |
| Overall Report.txt | Revenue & analytics    |

---

🧠 Key Concepts Demonstrated  
- File handling (read, write, append)  
- Dictionaries & lists  
- Input validation  
- Role-based access  
- Modular programming  
- Real-world business logic  
- Unique ID generation  
- Date & time handling  

---

▶ How to Run the Program  
1. Ensure Python 3 is installed.  
2. Place the script in a folder.  
3. Run the program:  
   ```bash
   python main.py
