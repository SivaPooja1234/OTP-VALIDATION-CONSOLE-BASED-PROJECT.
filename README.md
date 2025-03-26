# OTP-VALIDATION-CONSOLE-BASED-PROJECT.
Here's a `README.md` file for your GitHub repository:  

---

## OTP Validation - Console Based Project  

This is a simple console-based OTP validation project that sends a randomly generated OTP to a list of email addresses and verifies user input.  

### Features  
- Sends OTP via email using SMTP.  
- Verifies user-entered OTP.  
- Uses a secure connection with TLS.  

### Prerequisites  
- Python 3.x  
- `smtplib` (built-in)  
- `random` (built-in)  
- `email.mime` (built-in)  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```  
2. Install dependencies (if needed):  
   ```bash
   pip install smtplib email  
   ```  

### Usage  
1. Modify the list of email recipients in the script.  
2. Update the sender's email and app password in the script.  
3. Run the script:  
   ```bash
   python OTP_VALIDATION-CONSOLE-BASED-PROJECT.py
   ```  
4. Enter the received OTP when prompted.  

### Security Note  
- Do **not** hardcode sensitive credentials in your script. Use environment variables or a `.env` file.  
- Enable 2FA and use an app password instead of your main email password.  
