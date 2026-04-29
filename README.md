# Pill-Pall-An-Intelligent-AI-Powered-Healthcare-Management-System-
# PillPall

PillPall is a comprehensive Electronic Doctor Assistant Interface (EDAI) designed to streamline healthcare workflows for doctors, patients, and staff. It provides secure authentication, prescription management, lab test tracking, and more, all within a modern web interface.

## Features

- **User Authentication:** Secure login and registration for doctors, patients, and staff.
- **Doctor Dashboard:** Manage consultations, view patient records, and generate prescriptions.
- **Patient Dashboard:** Access prescriptions, view lab test results, and manage appointments.
- **Staff Modules:** Dedicated interfaces for lab technicians, pharmacists, and receptionists to handle daily operations efficiently.
- **Prescription Management:** Create, view, and download prescriptions in PDF format.
- **Lab Test Tracking:** Track and update lab test statuses.
- **Role-Based Access:** Custom dashboards and permissions for each user type.
- **Modern UI:** Responsive design with clear navigation and user-friendly workflows.

## Project Structure

```
app.py
extensions.py
gemini_helper.py
main.py
models.py
pdf_generator.py
seed_database.py
routes/
    __init__.py
    auth.py
    doctor.py
    main.py
    patient.py
    staff.py
static/
    css/
    images/
    js/
templates/
    base.html
    landing.html
    auth/
    doctor/
    patient/
    staff/
```

## Getting Started

### Prerequisites
- Python 3.8+
- pip
- Virtual environment tool (optional but recommended)

### Installation
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd "EDAI PillPall"
   ```
2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On Unix or MacOS
   source venv/bin/activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set up the database:**
   ```bash
   python seed_database.py
   ```
5. **Run the application:**
   ```bash
   python app.py
   ```

### Configuration
- Update configuration settings in `app.py` or use environment variables as needed.
- Static files are located in the `static/` directory.
- Templates are in the `templates/` directory.

## Usage
- Access the application at `http://localhost:5000` (or the configured port).
- Register as a doctor, patient, or staff to access respective dashboards.
- Doctors can manage consultations and prescriptions.
- Patients can view their prescriptions and lab results.
- Staff can access their specialized modules.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Flask Web Framework
- Jinja2 Templating
- Bootstrap CSS
- Google Gemini API (if used)

---

For more information, see the documentation or contact the project maintainer.
