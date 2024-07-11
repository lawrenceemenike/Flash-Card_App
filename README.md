# Flash Card App
This simple app helps you learn French vocabulary by flipping flashcards. It's built using Python's Tkinter library and reads from a CSV file to provide a user with an easy learning experience.

# Features
1. Interactive Flashcards: View French words and their English translations.
2. Automated Card Flipping: Cards flip automatically after 3 seconds to reveal the English translation.
3. Track Your Progress: Mark words as known to focus on unfamiliar vocabulary.

# How to Use
1. Run the App: Start the app to see a flashcard with a French word.
2. Learn the Word: The card will flip after 3 seconds to show the English translation.
3. Mark as Known: Click the check button if you know the word.
4. Next Card: Click the cross button to see the next word.
5. Save Progress: Known words are saved to a CSV file to keep track of your progress.

# Installation
1. Clone the repository: `git clone https://github.com/lawrenceemenike/flash-card-app.git`

2. Install the required packages.

3. Run the app: `python flash_card_app.py`

4. File Structure
data/french_words.csv: Contains the French words and their English translations.
data/words_to_learn.csv: Stores the words you need to learn.
images/: Contains images for the card fronts, backs, and buttons.

# Notes
Ensure that the CSV files and images are in the correct directories.
The app handles missing files gracefully and initializes from the original dataset if needed.
