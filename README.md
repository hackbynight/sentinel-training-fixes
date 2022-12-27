# sentinel-training-fixes
Collection of edits and work arounds for the sentinel training docs found on the [official repository for the full lab](https://github.com/Azure/Azure-Sentinel/tree/master/Solutions/Training/Azure-Sentinel-Training-Lab).


+ Add a watchlist with _HighRiskApps data during deployment in module 1 or modules 4+ won't work.
   
      1. search 'deploy a custom template' from top bar  
      2. click build your own template in editor  
      3. copy the json from missing-watchlist.json into the builder and save  

+ Broken TenableIOVulnerabilities function with error: 'detected multiple functions...'
   
      1. delete TenableIOVulnerabilities from logs>functions>Workspace functions> 
      2. install from content hub sentinel>content hub>search solution>reinstall 
      3. see solution file here or on official sentinel repo>...>solutions

etc
