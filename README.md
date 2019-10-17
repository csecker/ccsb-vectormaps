# ccsb-vectormaps
Generating vector maps from human ORFeome V7.1 clones

## What it does

Python script, which will, given a list of CCSB human ORFeome clones, pull the ORF sequence from http://horfdb.dfci.harvard.edu/hv7/ and generate annotated vector maps (*.gb) for:

### Gateway® pDONR™ vectors

    pDONR201
    pDONR221
    pDONR223

### LuTHy vectors (Trepte et al. MSB 2018)

    pcDNA3.1 PA-mCit-GW
    pcDNA3.1 myc-NL-GW
    pcDNA3.1 GW-mCit-PA
    pcDNA3.1 GW-NL-myc

## How to use it?

Simply replace input.csv with a list of CCSB clones (each line one ID, e.g. CCSB_14339) and then run the script. 
You can then choose (1-7) which vector maps to generate.

## Authors

* Christopher Secker
    
## License

This project is licensed under the GPLv3 license - see LICENSE file for details
