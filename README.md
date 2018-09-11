# NuSMV Model Verification Module
Installing NuSMV: 
1. ```brew install nusmv``` -- Installs the NuSMV CLI on your MAC. For other operating systems, google it.

## Running NuSMV Model Verification Programs: 
1. Open NuSMV in the terminal ```nusmv -int```
2. Read the NuSMV model file: 
```
$read_model -i {FILE_NAME}.smv
$flatten_hierarchy
$encode_variables
```
3. To verify the model against requirement, use: 
``` 
$check_ltlspec -p "G {YOUR_EXPRESSION}"
```
