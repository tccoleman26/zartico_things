# rdp_path_segmentation

# Introduction
---
> This Notebook and (subsequent paper) is about how sensor noise can effect trajectory data, how much that can effect trajectory data, and steps forward on how to remedy that problem.

> For example, if an entity is walking down Rodejo Drive in Beverly hills, we can surmize that the person is walking on the side walk, and not in the middle of the street. However, if the GPS data says the entity is in the middle of the street and moving under 3 Miles per Hour, at a near constant rate, that is probably a person and not a car. And t hat phenomenon is called sensor drift. 

> To study this, we are going to go through this in steps, and this paper is split into sections to describe these steps. The first section investigating how noise effects $y=x$ and how the Ramer Douglas Peucker Algorithm can alieviate some noise. The Second section covering how the RDP can alleviate geospatial trajectory data noise. And the third covering how to use machine learning can reduce noise for every line segment and reduce data at the same time.

