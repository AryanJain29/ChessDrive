

# ChessDrive Project

## Overview
ChessDrive is an innovative system that encodes and stores binary data within chess games, utilizing the Portable Game Notation (PGN) format for data storage and exchange. This project leverages the Lichess API to automate chess gameplay, facilitating a novel and secure form of data transmission.

## Key Features
- **Data Encoding**: Converts binary files into sequences of chess moves, encoding them into PGN.
- **Automated Gameplay**: Utilizes bot accounts on chess platforms to automate the gameplay required for data transmission.
- **Secure Storage**: Uses the PGN format of recorded chess games as a secure storage medium.

## Core Technologies
- Python
- Lichess API
- PGN format for chess games


### Encoding Data
To encode binary data from a file into a sequence of chess moves and save them in PGN format, use the `encode` function:

```python
def encode(file_path: str):
    """
    Summary:
    - Read binary data from file
    - Initialize chessboard
    - Generate legal moves and assign binary values
    - Process data in chunks and execute moves
    - Check for terminal states and save PGN
    - Return PGN string
    """
    # Implementation goes here
```

Example of calling the `encode` function:
```python
pgn_string = encode('path_to_your_binary_file')
print(pgn_string)
```

### Decoding Data
To decode data from a PGN string and reconstruct the original file, use the `decode` function:

```python
def decode(pgn_string: str, output_file_path: str):
    """
    Summary:
    - Load games from PGN string
    - Initialize chessboard
    - Convert moves to binary and write to output file
    - Print success message
    """
    # Implementation goes here
```

Example of calling the `decode` function:
```python
decode(pgn_data, 'output_file_path')
```

