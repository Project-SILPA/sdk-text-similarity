Usage
=====

### Note :
This module is still under development and this document presently shows only currently available utilities.

#### To get text similarity value
```
        TextSimilarity ts = new TextSimilarity();
        double val = ts.compare("Julie loves me more than Linda loves me", "Jane likes me more than Julie loves me");

```
The above function `ts.compare` returns a double number between 0 - 1 indicating text similarity.


#### Get module name and information
```
        TextSimilarity ts = new TextSimilarity();
        String moduleName = obj.getModuleName();
        String moduleInforamtion =  obj.getModuleInformation();
```

#### To run tests
Tests present at `/src/test/java/`

  - Select test to run
  - Right Click -> Run Test -> Run as Android Test

