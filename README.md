💰**CLI Digital Wallet (Python)**
A command-line based digital wallet system built using Python and SQLite. This project simulates basic financial operations like user authentication, balance management, and peer-to-peer transfers with a simple and interactive console interface.

***🚀Features***
🔐 User Registration & Login (hashed password & PIN)
💵 Add Funds to Wallet
🔄 Transfer Money Between Users
🎁 Random Cashback Rewards (on transfers)
📊 Transaction History Tracking
🗄️ SQLite Database Integration

***🛠️Tech Stack***
Python 3
SQLite3
hashlib (SHA-256)
Random module

**📂 Project Structure**
.
├── wallet.db        # SQLite database (auto-created)
├── main.py          # Main application script

***⚙️ Setup & Run**
Clone the repository:
git clone https://github.com/chaitanyasiri561/digital-wallet.git
cd your-repo-name
Run the application:
python main.py

***🧪 How It Works***
Users can register with a username, password, and 4-digit PIN.
Login grants access to wallet operations.
Transfers require PIN verification.
Each transaction is stored in the database.
Cashback is randomly applied (1%–5%, 30% chance).

***⚠️ Disclaimer***
This project is for educational purposes only. It does not implement production-level security practices and should not be used for real financial transactions.

***📌 Future Improvements***
Use bcrypt for stronger password hashing
Replace float with decimal for accurate money handling
Add REST API (Flask/FastAPI)
Implement user session management
Add UI (Web or Mobile)

***👨‍💻 Author***
Guduru Chaitanya Siri
B.Tech CSE, SRM University AP
