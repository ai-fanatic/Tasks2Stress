# Tasks 2 Stress

## Overview

Tasks 2 Stress is a web application designed to help users identify and manage their stress triggers by organizing tasks and their associated stress levels. Users can add tasks, assign stress levels, mark tasks as completed, and export their task lists to CSV format.

## Features

- **Task Management**: Add, edit, and delete tasks with associated stress levels.
- **Stress Level Slider**: A range slider to assign stress levels from 1 (low) to 5 (high).
- **Completed Tasks**: View and manage completed tasks in a separate section.
- **CSV Export**: Export tasks and completed tasks to a CSV file for easy sharing and analysis.
- **CSV Import**: Upload a CSV file to import tasks into the application.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- [PapaParse](https://www.papaparse.com/) for CSV parsing
- [Sortable.js](https://sortablejs.github.io/Sortable/) for drag-and-drop functionality
- [Canvas Confetti](https://github.com/catdad/canvas-confetti) for celebratory animations

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, etc.)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tasks2stress.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tasks2stress
   ```
3. Open `Tasks2Stress.html` in your web browser.

### Usage

1. **Adding Tasks**: Enter a task in the input field and select a stress level using the slider. Click the "Add Task" button to save it.
2. **Editing Tasks**: Click the edit icon next to a task to modify its text.
3. **Completing Tasks**: Check the checkbox next to a task to mark it as completed. Completed tasks will move to the "Completed Tasks" section.
4. **Clearing Completed Tasks**: Click the "Clear Completed Tasks" button to remove all completed tasks from the list.
5. **Exporting Tasks**: Click the "Export to CSV" button to download your tasks as a CSV file.
6. **Importing Tasks**: Click the "Upload CSV" button to select a CSV file and import tasks.

### File Structure

/tasks2stress
│
├── Tasks2Stress.html # Main HTML file for the application
└── README.md # Project documentation

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Thanks to the developers of the libraries used in this project for their excellent work.
