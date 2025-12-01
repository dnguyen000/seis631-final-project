# SEIS 631 Final Project

## Description
Sourced information contains the following information about an artist (Billy Strings):
- Date of event
- Venue of event
- City/State event
- Setlists:
  - Set number
  - Songs in setlist
  - Encore yes/no

To demonstrate theories learned in this course, I would like to answer the following information:
- What are the average number of songs in a setlist (not including encores) before and after the fiddler joined the band (July 3, 2022)

The above question allows for the data to be split into two groups: before and after July 3, 2022. From that, a permutation test can be ran to get collect the average setlist length and plot the histogram.

Confidence Interval calculation: This will require bootstrapping. Process TBD

## Source
- Setlist information: https://www.setlist.fm/setlists/billy-strings-73c3fe21.html
- Crawler: the code was derrived from ChatGPT. This allowed for the data to be scrapped from the page and output as a array JSON.