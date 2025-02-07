# AI TASK MANAGEMENT WITH CALENDER


This project is a web-based Task Manager with an integrated interactive calendar, enabling users to:

- Add tasks with details such as name, description, email, start time, and end time.
- Automatically mark tasks as complete when the end time is reached.
- Display notifications for task reminders and task completion.
- View tasks in an attractive calendar interface, color-coded by month and showing task details on assigned dates.

## Featuresa

### Task Management
- Add tasks with a user-friendly form.
- View all tasks in a list format.
- Automatically update tasks to "Completed" when the deadline is reached.

### Calendar Integration
- Interactive calendar with buttons for days and bolded month names.
- Tasks are displayed on their respective start and end dates.
- Color-coded months for easy navigation.
- Dynamic calendar generation for a one-year range starting from the current date.

### Notifications
- Send email notifications for:
  - Task reminders (one hour before the end time).
  - Task completion (when the task's end time is reached).
- Display visual alerts on the webpage for task updates.

## File Structure

### HTML
The main structure of the project is defined in `index.html`.

### CSS
Styling for the application is handled in `styles.css` to ensure an attractive and responsive design.

### JavaScript
The logic and interactivity are implemented in `scripts.js`:
- Task creation, validation, and calendar updates.
- Notification scheduling and task auto-completion.

### Server-Side Code
The backend (written in Python using Flask) handles:
- Task storage and management.
- Sending email notifications using SMTP.
- Calendar synchronization.

## Getting Started

### Prerequisites
- Python 3.x
- Flask
- A valid email account for sending notifications (SMTP setup required).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/JMadhan1/Ai-Task-Management-with-calender
   cd Ai-Task-Management-with-calender
   ```
2. Set up a virtual environment and install dependencies:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   pip install -r requirements.txt
   ```
3. Update the email configuration in `app.py` with your SMTP server details.

4. Run the Flask server:
   ```bash
   python app.py
   ```
5. Open `index.html` in your browser or navigate to the hosted address (e.g., `http://127.0.0.1:5000`).

### Usage
1. Add tasks using the form in the "Add New Task" section.
2. View all tasks in the "Task List" section.
3. Use the calendar to see tasks assigned to specific dates.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.

## Acknowledgments
- [Flask](https://flask.palletsprojects.com/) - Web framework.
- [FullCalendar](https://fullcalendar.io/) - Calendar integration (if applicable).

---

For any issues or suggestions, please contact [jmadhanplacement@gmail.com].


