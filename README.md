# Wireless and Mobile Networks Calculator 📡

## Description
This project serves as a practical tool for computing various metrics crucial in the field of wireless and mobile networks. The application supports calculations for sampler and interleaver configurations, OFDM parameters, power transmission calculations, throughput computations, and cellular system design. Each calculation module integrates specific formulas and considerations unique to the field of telecommunications, making it an invaluable educational and professional tool.

### Key Features:
- **Dynamic Form Fields**: Depending on the selected calculation type, the application dynamically generates the necessary input fields, demonstrating advanced DOM manipulation.
- **Asynchronous JavaScript**: Implements `async` and `await` for making asynchronous requests to the server for calculation processing, ensuring the UI remains responsive.
- **Flask Server**: Utilizes Flask for the backend to handle API requests and serve the application, illustrating how Python can be employed in server-side development.
- **Data Handling**: Temporarily stores input data on the server to process calculations, showcasing server-side data management.

## Technologies Used:
- **HTML/CSS**: For structuring and styling the user interface.
- **JavaScript**: For client-side scripting to manage user interactions and dynamically update the UI.
- **Python Flask**: For server-side logic, handling API requests and responses.

## Setup and Installation
Ensure you have Python and Node.js installed on your system to set up and run this project.
- Navigate to the project directory:
  ```bash
  cd FolderPath
  ```
- Install Python dependencies:
  ```bash
  pip install flask flask-cors
  ```
- Start the Flask server:
  ```bash
  python app.py
  ```

# How to Use
- Open your web browser and go to http://localhost:5000/ to access the calculator.
- Select the desired calculation type from the dropdown menu and fill in the required input fields.
-Then click the "Calculate" button to see the results.

# Calculation Types:
- Sampler and Interleaver: Enter parameters like bandwidth, number of bits per sample, and select interleaver bits.
- OFDM: Define bandwidth, number of subcarriers, and other related parameters.
- Power Transmitted: Input various gains, losses, and power levels to compute the transmitted power.
- Throughput: Configure the system for throughput calculations based on different access methods.
- Cellular System Design: Calculate essential parameters for designing a cellular system

## Sample Calculations

### Sample Calculator Interface
<p align="center">
  <img src="https://github.com/user-attachments/assets/cbf4c20c-145d-4e07-923e-cd764e95ec1d" width="900">
</p>

### Sample Result
<p align="center">
  <img src="https://github.com/user-attachments/assets/fa9bdf7d-ffc8-4ca1-80d6-8783ff954765" width="600">
</p>
