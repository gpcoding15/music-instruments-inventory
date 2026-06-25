
# Musical Instrument Class

This is a simple Python exercise from freeCodeCamp focused on practicing **Object-Oriented Programming (OOP)** concepts.

## Description

The project defines a `MusicalInstrument` class with two attributes:

* `name`: the name of the musical instrument
* `instrument_type`: the family or category of the instrument

The class also includes two methods:

* `play()`: prints a message saying that the instrument is fun to play
* `get_fact()`: returns a short fact about the instrument and its family

## Code Example

```python
instrument_1 = MusicalInstrument('Oboe', 'woodwind')
instrument_2 = MusicalInstrument('Trumpet', 'brass')

instrument_1.play()
print(instrument_1.get_fact())

instrument_2.play()
print(instrument_2.get_fact())
```

## Expected Output

```bash
The Oboe is fun to play!
The Oboe is part of the woodwind family of instruments.
The Trumpet is fun to play!
The Trumpet is part of the brass family of instruments.
```

## What I Practiced

* Creating a Python class
* Using the `__init__` constructor
* Defining instance attributes
* Creating and calling methods
* Instantiating multiple objects from the same class

## Technologies Used

* Python 3

## How to Run

1. Clone this repository.
2. Make sure Python is installed.
3. Run the file with:

```bash
python main.py
```

## Author

Created as part of my Python practice with freeCodeCamp.
