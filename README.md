# Board Game & Video Game Rental Management System

A Python-based rental management system developed in Google Colab for a board game and video game store.

The application allows customers to search for games, rent and return games, submit game feedback, manage subscriptions, and book in-store gaming sessions with friends. Managers can monitor inventory usage, analyse rental trends through visualisations, and identify games that may be suitable for inventory pruning.

## Features

### Customer Functionality

- Search available board games and video games
- Rent games from the store
- Return rented games
- Submit game feedback
- Manage subscriptions
- Book in-store gaming sessions
- Schedule bookings up to one month in advance
- View booking and rental information

### Manager Functionality

- Search inventory
- View rental frequency statistics
- Generate inventory visualisations using bar charts
- Identify underused games that may be candidates for inventory pruning
- Analyse store usage data to support business decisions

## Technologies Used

- Python
- Google Colab
- Matplotlib
- ipywidgets
- File Handling
- Data Visualisation

## Skills Demonstrated

- Data analysis
- Data visualisation
- User interface design using widgets
- Inventory management systems
- Date and time handling
- File processing
- Business data analysis
- Python programming

## Running the Project

1. Open the notebook in Google Colab.
2. Upload all required project files to the Colab environment.
3. Run all notebook cells.
4. Follow the on-screen menus and controls.

**Note:** The project relies on external data files that must be uploaded to Google Colab before execution. Instructions for uploading the files are included at the beginning of the notebook.

## Project Structure

```text
Board-Game-Rental-System/
├── Game-Store_Manager.ipynb
├── Board_Game_Info.txt
├── Video_Game_Info.txt
├── Rental.txt
├── Booking.txt
├── Game_Feedback.txt
├── Subscription_Info.txt
├── feedbackManager.pyc
├── subscriptionManager.pyc
└── README.md
```

## Future Improvements

- Replace text-file storage with a relational database
- Add user authentication and account management
- Develop a standalone desktop application
- Improve reporting and analytics features
- Add inventory forecasting and demand prediction
- Deploy the application outside of Google Colab

## Author

David — Computer Science & Artificial Intelligence Student at Loughborough University.
