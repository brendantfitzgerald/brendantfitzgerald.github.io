## Garbage Collection and Restoration
Universe branches are created from their parent every zeptosecond.  
Despite our best efforts, many are still created that immediately experience singularity or show signs of non-termination.  
These are easy enough to handle. Use the __InstanceRemoval.sh__ script to stop the instance, generate a log file, and mark the resources as "available".  

Occasionally, the instance owner will request that instances be terminated outside of those circumstances.  
They __need__ to submit the "Instance Termination" form signed by the owner or registered assistant.  

__Don't delete an instance manually.__  
In the rare case where we need to restore an instance, __RestoreInstanceV3.sh__ uses the __InstanceRemoval.sh__ log file.  
Otherwise it's another manual process and means sitting down with the (former) owner.  
That's also why __Instance Removal.sh__ requires the serial number of the "Instance Termination" form that the instance owner (or assistant) completed.   
Any restoration request __will__ be addressed at the next departmental review board, so we need all of our boxes checked.    

## Merging Instances
But sometimes a branch universe mirrors the parent universe too closely.  
Obviously running two nearly identical universes is a waste of resources.  
Previously, we'd just pick one of the two instances to remove, but this was a manual process resulting in data loss.  
Thanks to @Harv, we're running __HarvsUniversalDeDupe__ (or __HUDD__).[^1]  
Using the resources of less than one instance, we can check every branch universe against its parent and algorithmically decide which to merge.  


### Common Merge Issues
Currently, the comparison runs 3.1556952E+28 zeptoseconds after the branch universe's creation.  
Initially, we waited longer to compare, but sapient objects were inconsistently affected by the merged data, leading to the collapse of at least one 
sapient group structure, and the loss of one class's research project for the semester.  

__HUDD__ v1.1 added a new path for merging data into sapient objects utilizing the ```.dream()``` method.[^2]  
v1.1.1 added a check for diff size and sapient consciousness status.[^3]  

__Make changes to merge parameters in a test universe first.__  

```.dream()``` can also be a valid method for non-sapient objects.  
This usually isn't a problem, but some forms of Calcium objects can ```.dream()``` and are ```.conscious```, and don't have a ```.sleep()``` method, so will never be ```!objectID.conscious```.  
Besides error messages in the logs, we haven't seen any issues merging these objects.  

__HUDD__ v1.2.4 added a check for ```.observed``` and ```size``` status on merged objects.[^4]  
Anything larger than a lepton defaults to the location of the ```.observed``` object, but special considerations have to be made for smaller objects.  

## Interference  
Since we now provide support and resources outside of physics, we've had more requests for more granular and ongoing universal manipulations, usually centered around sapient group structures.  
As long as they have the proper forms signed by the proper people, there's not much we can do.  
See if we have a script in our repository, and scope the change.  
__Interfere.sh__ has options for ```MakeWeather()``` and ```MakeSapient()```. That should handle 80% of the requests that come in.  

Left to go on long enough, sapients develop 

[^1]: https://en.wikipedia.org/wiki/Black_hole#History
[^2]: https://en.wikipedia.org/wiki/D%C3%A9j%C3%A0_vu#Etymology
[^3]: Calling ```.dream()``` for a large diff on sapient objects where ```objectID.conscious``` led to [massive changes in sapient group structure](https://en.wikipedia.org/wiki/Religion)
[^4]: https://en.wikipedia.org/wiki/Louis_de_Broglie#Matter_and_wave%E2%80%93particle_duality
