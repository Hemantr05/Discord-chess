# Discord-chess
Allows machine learning to decide moves


## Installation

### If you want to use the stockfish chessbot 

1. Open terminal and clone this repository to desired directory location

2. Download stockfish bot

`wget https://www.dropbox.com/sh/75gzfgu7qo94pvh/AACk_w5M94GTwwhSItCqsemoa/Stockfish%205/stockfish-5-linux.zip`

3. Unzip the stockfish bot

`unzip ./stockfish-5-linux.zip`

4. Change permissions

`chmod +x stockfish-5-linux/Linux/stockfish_14053109_x64`

Making the following changes to the code base:

1. Comment out line 195 and 218 from commands/move.py - to enable stockfish

2. Comment line 192 and 214 from commands/move.py - to disable other method of reading move 
