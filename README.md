# Momo Transaction SMS Parser

This project is a simple but useful tool built to help users better understand and manage their Mobile Money (MoMo) transactions. In places like Rwanda, where MoMo is heavily used, users receive SMS alerts for every transaction—receiving money, sending payments, withdrawing cash, or buying bundles. These messages add up fast, making it difficult to track them manually.

## What the System Does

This app reads exported SMS messages from a file, extracts key details, and saves them neatly in a local database for easy viewing. If a message can't be understood, it's logged for review so the system can be improved.

It performs the following tasks:
- Identifies the **type of transaction** (e.g. payment, withdrawal, money received)
- Extracts the **amount**, **date**, and **participants** involved
- Saves valid data to a **SQLite database**
- Logs unrecognized messages in a separate file for debugging

## Project Structure
![Alt text](images/Screenshot%202025-06-18%20161929.png)

## Technologies Used

- **Node.js** – for backend logic and file processing
- **SQLite** – lightweight local database
- **xml2js** – Node.js library for converting XML to JavaScript objects
- **HTML/CSS/JS** – for building the dashboard interface

##  How to Run the System

1. **Install Node.js** on your machine.
2. Clone or download this repository.
3. Install the necessary packages:
   ```bash
   npm install xml2js sqlite3

## Live Demo & Resources
[Click here to watch a video demo!]( https://www.awesomescreenshot.com/video/41024162?key=fe16e270421e99ab6cddd6b127d9965c/)

 [Click here to view our Summative Report!](https://docs.google.com/document/d/1Tutie5QXrz96GwMzCEbssANKIWGMtv0-FG3jfbM2rfk/edit?tab=t.0#heading=h.38onzmn50cpv/)

## Authors
Mukeshimana Josiane

Ntwali Ishimwe Christian

Prudence Tracey Browns

