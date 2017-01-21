# Dimple.js Mini-Project
This is a remake of the first graph on here: http://www.businessinsider.com/the-27-worst-charts-of-all-time-2013-6?op=1/#wow-multicolor-3-d-cylinder-bar-charts-are-a-really-really-bad-way-to-articulate-relatively-simple-data-19

# How to Run
1. Clone the repo (duh!)
2. Make sure Python is installed (it probably is)
3. Navigate to the root directory of this repo
4. Start that simple server: `python -m SimpleHTTPServer`
5. Navigate to http://localhost:8000

# What Exactly Am I Looking At?
There are 2 graphs on this page:

1. **The first:** an animated graph that cycles through the 4 quartiles. This highlights the differences between values as a trend -- you can see how the values progress form Q1 to Q4
2. **The second:** this is a set of 4 smaller graphs that allows you to view all four quartiles at once. It takes longer to see the trends and differences between the graphs, but without the animation, you get the chance to examine each graph at your leisure.

# Credit
Graph-drawing code was based on: http://dimplejs.org/advanced_examples_viewer.html?id=advanced_trellis_bar
Data was manually scraped by me. Animation was a gimme from Dimple.js (yay!).
