# Flash Cards Learning Application

A desktop application that helps you learn French vocabulary through interactive flash cards. The application presents French words and their English translations, allowing you to track your progress and focus on words you need to practice more.

## Features

- Interactive flash card interface
- Automatic card flipping after 3 seconds
- Progress tracking system
- Mark cards as known/unknown
- Persistent learning progress
- Clean and intuitive user interface
- Beautiful card design with front and back views

## Requirements

- Python 3.x
- Tkinter (built into Python standard library)
- pandas
- numpy

## Installation

1. Clone this repository:

```bash
git clone https://github.com/momed-ali01/flash_cards.git
cd flash_cards
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python main.py
```

### Flash Card Controls

- Right Button (✓): Mark the current word as known
- Wrong Button (✗): Mark the current word as unknown and keep it for review
- Cards automatically flip after 3 seconds to show the translation

### Learning Process

1. The application starts by showing a French word
2. After 3 seconds, the card flips to show the English translation
3. Click the check mark if you knew the word, or the cross if you didn't
4. Words you mark as known are removed from the learning deck
5. Your progress is automatically saved

## Data Structure

The application uses two CSV files:

- `data/french_words.csv`: Contains the complete French-English vocabulary list
- `data/words_to_learn.csv`: Tracks the words you still need to practice

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
