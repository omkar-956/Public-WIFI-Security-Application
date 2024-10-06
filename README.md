# Public-WIFI-Security-Application

Public Wi-Fi Security Scanner🔎
This project is a Flask-based web application that simulates scanning for nearby public Wi-Fi networks and provides information on their security levels. It demonstrates a basic approach to identifying and displaying network security risks, which could be useful for users trying to assess the safety of connecting to public Wi-Fi.

Features💡
Simulates scanning public Wi-Fi networks.
Displays network SSID, security protocol, and risk level (e.g., secure, insecure, malicious).
Interactive front-end that fetches and displays Wi-Fi networks in real time.
Technologies Used
Python (Flask): To handle the backend and API routing.
HTML/JavaScript: For rendering the user interface and performing front-end tasks.
JSON: For exchanging data between the front-end and back-end.
Requirements
Python 3.x
Flask (pip install Flask)
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/public-wifi-security-scanner.git
Navigate to the project directory:

bash
Copy code
cd public-wifi-security-scanner
Install the required Python packages:

bash
Copy code
pip install Flask
Run the Flask application:

bash
Copy code
python app.py
Open a web browser and go to http://127.0.0.1:5000/ to access the app.

Project Structure🗂️
app.py: The main application file that defines routes, network scanning logic, and serves the HTML template.
templates: (Optional) If you plan to extend the app with separate HTML files.
static: (Optional) To store additional assets like CSS or JavaScript if needed.
Simulated Networks
For demo purposes, the application uses a list of hardcoded networks. When the "Scan for Networks" button is clicked, it will display dummy data with various Wi-Fi security levels (e.g., WPA2, None).

Future Enhancements
Integrate actual network scanning capabilities using tools like scapy or iwlist.
Add more robust risk assessment algorithms based on security protocols.
Improve the UI/UX for a more interactive experience.
License
This project is licensed under the MIT License.
