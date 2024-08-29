# **SyncZ**

## Introduction

SyncZ brings a Matrix-inspired design to the world of online meetings, offering a sleek and immersive virtual collaboration experience. Dive into the digital realm with SyncZ, where communication meets a futuristic aesthetic.

## Features

### 1. User Authentication

- **Login/Registration:** Users can securely create accounts or log in to access SyncZ features.

### 2. Dashboard

- **Personalized Dashboard:** Navigate seamlessly through a user-friendly dashboard.

### 3. Meetings

- **Create Meetings:** Effortlessly schedule and host virtual meetings.
- **Join Meetings:** Enter virtual spaces using unique room IDs.

### 4. Matrix Aesthetics

- **Sleek Interface:** Enjoy a Matrix-inspired design for a futuristic and captivating visual experience.

## Getting Started

### Prerequisites

- Ensure you have Python and Flask installed on your machine.
- Clone the SyncZ repository.

### Installation

1. Set up a virtual environment.
   ```bash
   python -m venv venv
   ```

2. Activate the virtual environment.
   - **On Windows:**
     ```bash
     venv\Scripts\activate
     ```
   - **On macOS and Linux:**
     ```bash
     source venv/bin/activate
     ```

3. Install dependencies.
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the database.
   ```bash
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade
   ```

### Usage

1. Run the application.
   ```bash
   flask run
   ```

2. Access the application in your browser at `http://localhost:80`.

## Contributing

Contributions are welcome! If you have ideas for improvements or find any issues, feel free to open an [issue](link_to_issues) or submit a [pull request](link_to_pull_requests).

## License

This project is licensed under the [MIT License](link_to_license).

---

**SyncZ - Redefining Virtual Meetings with a Touch of the Matrix!**