# Office-Terminal

## Description
The Office Quotes Generator is a simple Python-based application that provides random quotes from the popular TV show The Office. The app retrieves quotes from different characters like Michael Scott, Dwight Schrute, Jim Halpert, and more. It also offers "That's What She Said" (TWSS) quotes and random quotes from the entire office.

Each quote is displayed with random ANSI colors to make the experience more fun and visually appealing.

## Features
Fetch random quotes from specific characters (e.g., Michael Scott, Dwight Schrute, etc.).
Retrieve random "That's What She Said" quotes.
Get random quotes from The Office without specifying a character.
ANSI color-coded output for a better experience.
Command-line interface for easy usage.

## Installation
Download the application using wget:
To install the application, you can use wget to directly download the script and quotes.json file. Run the following command in your terminal:

```
wget https://github.com/Bhautik-2004/office-terminal/releases/download/v1.0/office-terminal.deb
```

```
sudo apt install ./office-terminal.deb
```

Get a random quote from a specific character:
```
./main.py -c michael
```
Get a random "That's What She Said" (TWSS) quote:
```
./main.py -twss
```

To view all the available options, run:
```
./main.py -h
```
To convert a file from DOS (Windows) format to Unix format:
```
sudo dos2unix /usr/bin/main.py
```


## License
This project is licensed under the MIT License.
