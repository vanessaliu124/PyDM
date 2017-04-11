# PyDM
Using python to manage metadata and automate data modelling

## Goal
The ultimate goal is to achieve automate merging tables with complicated table relationships and document the data source
Raw data are Child Parent relationship table and metadata

## Sample relationship diagram
key	Child	Parent
1	   A	   B
2	   A   	 B
3	   A	   C
4	   B	   D
5	   B	   D
6	   X	   Y
7	   D	   E
8	   D	   E

## Idea
using the pandas data operation and merge(equivalent to SQL join) will create a nice data map for further analysis
