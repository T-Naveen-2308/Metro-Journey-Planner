# Metro Journey Planner

Metro Journey Planner is a web application that helps users plan their metro journeys efficiently. It uses Python with Flask for the backend and Vite with TypeScript for the frontend.

## Features

- **Journey Planning**: Users can enter their starting point and destination to get the shortest metro route.
- **Interactive Map**: Visual representation of the metro lines and stations for better user experience.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.

## Technologies Used

- **Backend**: Python, Flask
- **Frontend**: TypeScript, Vite, HTML/CSS
- **Mapping**: Leaflet (or any other mapping library you choose)

## Getting Started

### Prerequisites

- Python 3.x installed on your machine
- Node.js and npm (Node Package Manager)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/T-Naveen-2308/Metro-Journey-Planner.git
   cd metro-journey-planner
   ```
2. **Backend Setup:**

  ```bash
  # Install dependencies
  pip install -r requirements.txt
  ```
3. **Frontend Setup:**

  ```bash
  cd frontend
  # Install dependencies
  npm install
  ```
##Running the Application
1. **Run the Flask backend:**

  ```bash
  # Make sure you are in the root directory of the project
  python app.py
  ```

2. **Run the Vite frontend:**

  ```bash
  # Make sure you are in the 'frontend' directory
  npm run dev
  ```

3. **Open the Application:**

  Open your web browser and go to http://localhost:3000 to see the Metro Journey Planner application in action.
