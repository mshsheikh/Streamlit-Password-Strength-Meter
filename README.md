# Streamlit Password Strength Meter 🛡️

A secure and interactive password strength analyzer built with Streamlit. Generate strong passwords, evaluate their security, and get actionable feedback to improve your digital safety.

---

## Features ✨
- **Password Strength Analysis**: Instantly check the strength of your password.  
- **Secure Password Generator**: Generate random, secure passwords with customizable length.  
- **Actionable Feedback**: Get detailed suggestions to improve weak passwords.  
- **Recent Password History**: View the last 5 passwords you’ve analyzed (cleared on refresh).  
- **Modern UI**: Clean and user-friendly interface with smooth interactions.  

---

## Getting Started 🚀

### Prerequisites
- Python 3.8+ 🐍  
- Streamlit installed 📦  

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mshsheikh/Streamlit-Password-Strength-Meter.git
   cd Streamlit-Password-Strength-Meter
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run app.py
   ```

---

## Usage 🎮
1. **Analyze a Password**:
   - Enter a password in the input field.
   - Click **Analyze Password** to see its strength and improvement suggestions.

2. **Generate a Secure Password**:
   - Use the sidebar to specify the desired password length (8–32 characters).
   - Click **Generate Password** to create a strong, random password.

3. **View Recent Passwords**:
   - Check the sidebar for a list of recently analyzed passwords (last 4 characters visible).

---

## Customization 🛠️
- **Adjust Security Rules**: Modify the `check_password_strength` function in `app.py` to customize strength criteria.  
- **Styling Changes**: Update the CSS section at the top of `app.py` for visual tweaks.  

---

## Security Note 🔒
- Passwords are **not stored permanently** and are cleared when you refresh the page.  
- Always use a trusted password manager for secure storage of your passwords.

---

## Contributing 🤝
Contributions are welcome!  
1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature/fooBar`).  
3. Commit your changes (`git commit -am 'Add new feature'`).  
4. Push to the branch (`git push origin feature/fooBar`).  
5. Open a pull request.  

---

## License 📄
This project is MIT licensed.

---

Made with ❤️ by [Muhammad Salman Hussain](https://github.com/mshsheikh)
