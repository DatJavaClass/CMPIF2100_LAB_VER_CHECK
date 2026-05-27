# CMPIF2100 LAB VERSION CHECK
Two magic lines of script that will save your sanity

TL;DR:
import sys
print(sys.version)

Now something you'll really enjoy! 

If you run an instructor's code exactly as written and your output doesn't match what they show in the video, it looks like something is broken on your end. Often it isn't. A very common cause is that you and the instructor are running different versions of Python. Many Coursera worksheets were recorded on older versions, and behavior that was correct then can produce different results now.

This is what's actually happening

Python changes over time. Across versions, the language can adjust how certain operations work under the hood, how some functions format or return their output, what default settings a library uses, and which functions are available or deprecated. Most of these changes are small, but they are enough to make identical code produce different visible results on different versions.
A few common places this shows up:

Random number generation, where the same seed can produce different values on different versions.
Dictionary or set ordering, formatting of printed output, and rounding or float display.
Library functions that were renamed, changed defaults, or were removed entirely.

In all of these cases the instructor's result made perfect sense for the version they recorded on, and your result is correct for the version you are running. Neither one is wrong. They simply belong to different versions.
If the assignment is auto graded, the grader runs on the same kernel you do, so your numbers are the ones it expects. You do not need to match the video frame for frame.
How to use

Insert the following into cell 1 to confirm which version you are running:

  import sys
  print(sys.version)

The number before the first space is your Python version. If it differs from the version in the video, that often explains the mismatch. 

Nothing is broken and you are awesome.
