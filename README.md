# EC-based Reasoning System
Reasoning system based on Clingo.

## System
- OS:
    -- Windows 10
    -- Ubuntu
- Clingo - 5.4.0

## Folders
- ./clingo/ - Contrains clingo.exe and format-output files.
- ./lp/ - Contrains:
    -- activities.lp - affordances.  
    -- events.lp - happens.  
    -- sorts.lp - locations and objects of interests coming from low-level layer.  
    -- ecasp888.lp - events and fluents, effects of events and triggered event.  
    -- ecasp88888.lp - context predicates linking the affordances.  
    -- decOrigin2.lp - Discrete Event Calculus Axiomatization.    
    
- ./inference/ - contains the inference in file ecasp88.txt in line 15.  

- parserEC.ipynb - is the parser.  


## Important:
If permission denied, run:  
- $ chmod +x clingoLinux  
- $ chmod +x format-output