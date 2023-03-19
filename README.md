# Anki Flashcard Generator

Anki Flashcard Generator is a  Python script that automates the process of generating and adding Anki flashcards from a given text file. It leverages the GPT model provided by OpenAI and the AnkiConnect plugin. 

## Features

- Automatically generates Anki flashcards from a text file
- Utilizes OpenAI's GPT-3.5-turbo model for intelligent flashcard creation
- HTML formatting for better flashcard appearance and recall
- Simple setup and easy-to-use command line interface

## Prerequisites

- Anki desktop application installed and running
- AnkiConnect plugin installed in Anki
- OpenAI Python library
- OpenAI API key

## Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/anki-flashcard-generator.git
cd anki-flashcard-generator
```

2. Install the required Python libraries:

```
pip install -r requirements.txt
```

3. Set up the OpenAI API key.


## Usage

To generate flashcards from a text file, run the following command:

```
python anki.py /path/to/your/textfile.txt
```

