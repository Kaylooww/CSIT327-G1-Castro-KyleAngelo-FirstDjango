# CampusConnect — First Django Project

A Django project for **CSIT327** featuring user accounts and a dashboard.

## Student Information

- **Full Name:** Kyle Angelo C. Castro
- **Section:** G1
- **Course:** CSIT327

## Requirements

- Python 3.12 or newer
- pip

## How to Run the Project

1. **Clone the repository** and open the project folder:

   ```bash
   git clone https://github.com/Kaylooww/CSIT327-G1-Castro-KyleAngelo-FirstDjango.git
   cd CSIT327-G1-Castro-KyleAngelo-FirstDjango
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment:**

   **Windows (Command Prompt):**
   ```cmd
   .venv\Scripts\activate
   ```

   **Windows (PowerShell):**
   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

   **macOS / Linux:**
   ```bash
   source .venv/bin/activate
   ```

4. **Install Django:**

   ```bash
   python -m pip install "Django==6.1.2"
   ```

5. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

6. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

7. Open **http://127.0.0.1:8000/** in your browser.

## Main Pages

- `/` — Dashboard
- `/accounts/signup/` — Sign up
- `/accounts/login/` — Log in
- `/accounts/profile/` — Update profile
- `/admin/` — Django admin

## Notes

- Run commands from the folder containing `manage.py`.
- The project uses SQLite for local development.
- Keep the `.venv/` directory, `__pycache__/` files, database files, and secrets out of new Git commits using `.gitignore`.
- For deployments, move the Django `SECRET_KEY` out of `campusconnect/settings.py` into a secure environment variable and disable `DEBUG`.
