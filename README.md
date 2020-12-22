# ChessBot
The official repository for my Discord ChessBot


## Install Instructions

1. Clone this repo with 
`git clone https://github.com/qwertyquerty/ChessBot`
2. Make a virtual environment, and activate it
`pip install virtualenv`

On Linux
`python -m venv env`

On Windows
`py -m venv env`
 
 `source env/bin/activate`

3. Install all requirements with 
`pip3 install -r requirements.txt`

4. Run it with 
`python3 run_chessbot.py`


## Select bots to make move

### Stockfish chess bot

1. Open terminal

2. Download stockfish

`wget https://www.dropbox.com/sh/75gzfgu7qo94pvh/AACk_w5M94GTwwhSItCqsemoa/Stockfish%205/stockfish-5-linux.zip`

3. Unzip the bot

`unzip stockfish-5-linux.zip`

4. Change permission:

`chmod +x stockfish-5-linux/Linux/stockfish_14053109_x64`


### To run desired bot/algorithm

1. To enable stockfish:

- Comment out line 195 and 218 from chessbot/move.py 
- Comment line 192 and 214 from chessbot/move.py (to disable other bot)

2. To enable machine learning algorithm (Minimax):

- Commend out line 199 and 214 (if commented), from chessbot/move.py
- Comment line 195 and 218 (if not commented), from chessbot/move.py
