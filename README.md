# Space-Force

## Inspiration
The number of satellites and debris in space has signficantly increased in recent years, with around 19500 objects documented in 2019. Thanks to improvements in satellite technology and lower costs of production, we expect this number to rise even higher ... and more rapidly at that.

The increase in the number of satellites and space debris, however, also indirectly increases the risk of collision between them. While most collisions involve a satellite and piece of space debris, there are instances where collisions occurred between two satellites -- a scenario that could have been avoided.
## What it does
To help prevent these collisions from happening:

First, we analyzed a dataset presented by the International Data Analytics Olympiad 2020 to predict 7-day trajectories of 600 satellites in orbit.

Second, using the data we generated from our analysis, we created a 3d space to visualize and animate these satellite path trajectories to help proactively address any potential collision.
## How we built it
We used python and Jupyter notebooks to analyze the data, and we used three.js to visualize satellite trajectories.
## Challenges we ran into
On the machine learning (ML) side, there were performance (and time!) limitations, as sometimes the code would crash because of the taxing amount of resources to execute ML code.

Translating x, y, z coordinates from JSON files and animating satellite pathways in 3D space was the trickiest on the visualization side.
## Accomplishments that we're proud of
We made a space app! This was the first time we used three.js!
## What we learned
We learned how to perform ML predictions and visualize data using three.js!
## What's next for Space D
We'd love to host it on a platform for others to explore and play around with.
