# Banshee [![Build Status](https://travis-ci.org/NWChen/banshee.svg?branch=master)](https://travis-ci.org/NWChen/banshee)

`banshee` is a tool we're developing for the 1st Information Operations Command (LAND) of the U.S. Army as part of Columbia University's [Hacking 4 Defense](http://www.h4d.cs.columbia.edu) initiative.

## Team Members
```
Ori Aboodi, oda2102
Zach Boughner, ztb2003
Neil Chen, nwc2112
Alan Hytonen, ajh2217
Peter Richards, pfr2109
```

## Deployment
To run `banshee`, make sure you're running Python 3.5. `virtualenv` is recommended but not necessary. Make sure you have all necessary packages by running `pip install -r requirements.txt`. To start the app,
```bash
cd banshee
python server.py
```
and open your browser to `localhost:5000`.

## Contribution
If you've been added as a contributor to the project, follow these guidelines:

### First time contributing to this repo
```bash
git clone https://github.com/NWChen/banshee.git
git status
```
After you've made your changes,
```bash
git add <name of file/dir you changed>
git commit
git push origin master
```

### Not my first time contributing to this repo
If you're making changes to an existing feature, switch to the appropriate feature branch using `git checkout <name of branch>`. If you're developing a new feature (e.g. a new scraper module), then use `git checkout -b <name of feature`, which creates and switches to a new branch. Either way, afterwards you can update this repo with your changes via the following:
```bash
git add <name of file/dir you changed>
git commit
git push
```
