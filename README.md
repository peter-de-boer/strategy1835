# strategy1835

This repo contains scripts for parsing and analyzing rails 1835 logfiles.
You can find an article based on this analysis here: https://www.boardgamegeek.com/article/33473132#33473132

The directory logfiles contains the logs files of seventeen games, played with Rails (https://rails.sourceforge.io/). These files are just created by copy-pasting the text from the report window in Rails.

The directory statusfiles contains the status files from the same seventeen games. They were created by the File->Save game status menu at the end of the game.

The file analyze_games.ipynb is a jupyter notebook containing python code to read in the log and status files and to do analysis on that data.

To use it, git clone this repo, create an environment by `conda env create -f environment.yml`, and open the notebook by `jupyter notebook analyze_games.ipynb`.
