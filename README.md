# I-FeatExt-Craig
By Ryan Craig

## Goals
The goal of this project was to get a better understanding of feature extraction.
Using existing tool I was able to get a better understanding of how to do this.

## Tool/ Libraries
* [Wekinator](http://www.wekinator.org/downloads/)
* [Wekinator Input Helper](http://www.wekinator.org/input-helper/)
* [Micro:Bit](http://microbit.org/guide/)

⋅⋅⋅[Link to Hex code](http://www.doc.gold.ac.uk/~mas01rf/WekinatorDownloads/wekinator_examples/all_source_zips/RUN_THIS_ON_MICROBIT.hex)

⋅⋅⋅Download [BBC micro:bit](http://www.wekinator.org/examples/#BBC_microbit)


## What I Accomplished
With the help of Wekinator Input helper I was able to smooth out the x, y, and z axis being feed in from the accelerometer. These data points were jumping even when on a desk so I took the average of the points for 60 times. I also determined the acceleration off of the z axis.  

## ML Choices
For most of my choices I used the default Neural network or K- nearest neighbors. This would be good to detect acceleration values that can trigger a classifier based of the force felt. If the force is greater it triggers a warning to make sure the person or item is of after the accelerometer had a high reading.
