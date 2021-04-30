# mjgl-tools
This tool set will allow someone using OBS Studio to dynamically create graphics to display information from the [mahjsoul api](https://github.com/riichinomics/majsoul-api), including:
* The team logos of participants in each match being played in the next session
* The team logos of participants in a selected match within that session
* A graph of scores and current standings as displayed on the [riichi.moe](https://riichi.moe) site

Future features planned for the tool set include:
* Various stats such as riichi rate, dama rate, average hand points value, and more
* 0-4 stats of teams participating in a selected match in the current session
* 0-4 stats of a selected team or player
* Fantasy league points for a selected match in the current session.

## Installation
To install the tool suite, first download a tagged release from the [tags](https://github.com/woogers/mjgl-tools/tags) page. Extract the archive and set configuration options in config.ini using instructions in the Configuration section below.

### Configuration
There are currently three configurable options in config.ini:
* install_path: The absolute filepath to the directory where the MJSL OBS TOOLS directory is located
* contest_id: The contest id from the api for the contest you wish to grab data for. Set to /mjg/ league 2 by default
* api_url: http://riichi.moe/api by default

## Usage
Once configuration is complete, execute the tools by launching go.exe. You will be prompted to select which match you wish to get data for.