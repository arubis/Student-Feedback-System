# Student Feedback System

Full-stack Flask project with student login, admin login, and feedback management.

## How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Set up environment variables:
   ```bash
   # Generate a secure secret key
   export SECRET_KEY=$(python -c "import secrets; print(secrets.token_hex(32))")
   # Or manually set it:
   export SECRET_KEY="your-secure-secret-key-here"
   ```

3. Run the app:
   python app.py

4. Open browser at:
   http://127.0.0.1:5000/
