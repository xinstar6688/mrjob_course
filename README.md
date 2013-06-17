Setup for Big Dive
==================

1. Have a Github account (email your username to
   [steve+bigdive@steveasleep.com](steve+bigdive@steveasleep.com)
2. Clone this repository
3. `cd` to your local copy
4. `pip install -r requirements.txt`
5. Visit [Yelp Dataset Challenge](http://www.yelp.com/dataset_challenge/data)
   and get a copy of the Yelp data set
6. Put it in `mrjob_course/data/yelp`
7. Run `make`

Organization
============

* `data/`: All data to be used in exercises
* `exercises/`: Test cases and stub files for exercises
* `scripts/`: Some code I used to generate the data, ignore this
* `solutions/`: No peeking! Completed exercise code that can be copied over
  the stub files to work correctly.
* `syllabus.txt`: Overview of course order

Running exercises
=================

```
python exercises/<exercise>/test.py
```
