Overview
--------

This project contains evaluation-related material for linux drivers. It contains the `ifdeftoifStatistics.sh` script which starts the `#ifdef` to `if` process on linux driver files.


Preparation
-----------
1. `TypeChef` and `Hercules` folder must be at ".." relative to this project folder; see project [Hercules](https://github.com/joliebig/Hercules) to install both `TypeChef` and `Hercules`.
2. Run prepareLinux.sh to automatically download missing source files, system headers and create the required .pc files.
3. Execute the linux transformation with `./ifdeftoifStatistics.sh`.

Good luck. In case of problems contact someone of us.

Notes
-----------
This project is in an experimental stage. Further testing & validation has to be done.