## Garbage Collection and Merging Behavior
Universe branches are created every zeptosecond.  
Despite our best efforts, many are still created that immediately experience singularity or show signs of non-termination.  
These are easy enough to handle. Use the __InstanceRemoval.sh__ script to stop the instance, generate a log file, and mark the resources as "available".  

But sometimes a branch universe mirrors the parent universe too closely.  
Obviously running two nearly identical universes is a waste of resources.  
Previously, we'd just pick one of the two instances to remove, but this was a manual process resulting in data loss.  
Thanks to @Harv, we're running __HarvsUniversalDeDupe__ (or __HUDD__).[^1]  
Using the resources of less than one instance, we can check every branch universe against its parent and algorithmically decide which to merge.  


### Common Issues
Currently, the process runs 3.1556952E+28 zeptoseconds after the branch universe's creation.  
Initially, we waited longer to run the merge, but sapient objects were inconsistently affected by the merged data, leading to the collapse of at least one 
sapient group structure, and the loss of one class's research project for the semester.  

__HUDD__ v1.1 added a new path for merging data into sapient objects utilizing the ```.dream()``` method.[^2]  
v1.1.1 added a check for diff size and sapient consciousness status.[^3]  

__Make changes to merge parameters in a test universe first.__  

```.dream()``` can also be a valid method for non-sapient objects.  
This usually isn't a problem, but some forms of Calcium objects can ```.dream()``` and are ```.conscious```, and don't have a ```.sleep()``` method.  
Besides error messages in the logs, we haven't seen any issues merging these objects.  

__HUDD__ v1.2.4 added a check for ```.observed``` and ```size``` status on merged objects.  
Anything larger than a lepton defaults to the location of the ```.observed``` object, but special considerations have to be made for smaller particles.  

[^1]: https://en.wikipedia.org/wiki/Black_hole#History
[^2]: https://en.wikipedia.org/wiki/D%C3%A9j%C3%A0_vu#Etymology
[^3]: Calling ```.dream()``` for a large diff on sapient objects where ```objectID.conscious``` led to [massive changes in sapient group structure](https://en.wikipedia.org/wiki/Religion)
