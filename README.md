Nodepay.ai Bot
The Nodepay.ai Bot is a script designed to automate pinging using multiple proxies. It is optimized for farming on Nodepay.ai with support for multi-account and multi-proxy setups.

Register on Nodepay.ai

📋 Features
Supports multiple proxies to automate pinging tasks simultaneously.
Supports multiple accounts by storing tokens in the np_tokens.txt file.
Simple to set up on a server or local machine.
Real-time logs to monitor proxy ping results.
Ensures your account gets the Proof of Humanhood Badge.
🔄 Latest Update
Connection Limit per Account: Each account is now limited to connecting with a maximum of 10 proxies.
Solution: Create multiple accounts to optimize farming. This script supports multi-account setups by adding tokens to np_tokens.txt (one token per line).
🔑 How to Obtain the Required Information
Log in to your Nodepay.ai account: https://app.nodepay.ai/.
Press F12 or Ctrl + Shift + I to open the developer console.
In the console, enter:
javascript
Copy code
localStorage.getItem('np_token');
Copy the output (your NP_TOKEN) and paste it into the np_tokens.txt file (one token per line).
Additionally:

Add your proxies to the proxy.txt file in this format:
perl
Copy code
http://username:password@ip:port
🚀 How to Run the Script
Follow these steps to set up and run the Nodepay.ai Bot:

1. Clone the Repository
bash
Copy code
git clone https://github.com/Zlkcyber/nodepay.git
cd nodepay
2. Install Dependencies
bash
Copy code
pip install -r requirements.txt
3. Run the Script
bash
Copy code
python3 main.py
✅ Expected Output
If the script is running correctly, you will see logs like this:

perl
Copy code
2024-11-20 07:10:26 | Ping successful: socks5://bpwikvcq:l4sbomroi3gy@45.94.136.208:6984
2024-11-20 07:10:28 | Ping successful: socks5://bpwikvcq:l4sbomroi3gy@216.45.56.244:6262
📝 Notes
Ensure that each account added in np_tokens.txt has the Proof of Humanhood Badge.
Use valid proxies in the proxy.txt file to avoid connection issues.
You can monitor the logs to track the performance of each proxy and account.
📧 Support
For any issues or questions, feel free to contact:

Telegram: t.me/zlkcyber
GitHub: github.com/zlkcyber
Make sure to star ⭐ the repository if you find it useful!

This README provides clear instructions and a polished presentation for your project. Let me know if you'd like further enhancements! 🚀
