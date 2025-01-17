# Nereides_telemetry

 # Project Néréides: Telemetry with Raspberry Pi

## Description
Project Néréides is an initiative by the student association from UTT, competing in the Monaco Energy Boat Challenge. This project involves creating a boat from scratch and competing on various criteria such as speed, endurance, and ecological impact. The telemetry system uses a Raspberry Pi to collect and transmit data to different databases.

## How to Navigate
The project is organized into different Python scripts, each handling telemetry data for a specific database:
- `firebase_telemetry.py`: Script for sending data to Firebase.
- `supabase_telemetry.py`: Script for sending data to Supabase.
- `mongodb_telemetry.py`: Script for sending data to MongoDB.

Each script contains functions to generate data, get timestamps, check database connections, and send data to the respective database.

## Usage Examples
To run the telemetry scripts, use the following commands:

- **Firebase**:
  ```sh
  python firebase_telemetry.py
Supabase:


python supabase_telemetry.py
MongoDB:


python mongodb_telemetry.py
Each script will generate sample data, check the database connection, and send the data to the respective database.

Technical Decisions
The project uses Python for its simplicity and extensive library support. Key technologies and decisions include:

Firebase: Chosen for its real-time database capabilities and ease of integration.
Supabase: Selected for its open-source nature and comprehensive feature set.
MongoDB: Used for its flexibility in handling unstructured data.
Key Lessons from This Experience
Through this project, we learned the importance of:

Modular Code: Organizing code into separate scripts for each database made the project easier to manage and maintain.
Real-time Data Handling: Ensuring that data is sent and received in real-time is crucial for telemetry systems.
Cross-platform Compatibility: Using Python and Raspberry Pi allowed for a versatile and portable solution.
