# Qodana. Output formats

## Basic output
```
<output-directory>
-log 
-projectStructure
-profile.xml 
-.descriptions.json
-%InspectionId1%.json 
-%InspectionId2%.json  
-..................
-%InspectionIdN%.json
```
- **log**  - contains  `idea.log`, `gradle.log`, and so on.
- **projectStructure** - Metainformation about your project: modules, frameworks/libraries, roots, and so on.
- **profile.xml** - effective profile in the IDEA format: all inspections and their configurations. Depends on the configured profile, `qodana.yaml`, and the plugin list.
- **.descriptions.json** - descriptions for all inspections.
- **%InspectionId%.json** - contains all problems generated by the inspection with this ID: `%InspectionId%` message, place, severity, and so on.


## UI-compatible output

[TO DO]