# ccsb-vectormaps
Generating vector maps from human ORFeome V5.1/V7.1/V8.1 clones or custom ORFs.

## What it does

Python script, which will, given a list of CCSB human ORFeome clones, pull the ORF sequence from http://horfdb.dfci.harvard.edu/ and generate annotated vector maps (*.gb) for:

### Gateway® pDONR™ vectors

    pDONR223
    pDONR221
    pDONR201

### LuTHy vectors (Trepte et al. MSB 2018)

    pcDNA3.1-NL-N1
    pcDNA3.1-NL-C1
    pcDNA3.1-PA-mCit-N2
    pcDNA3.1-PA-mCit-C2
    pcDNA3.1-mCit-N2
    pcDNA3.1-mCit-C2

### N2H vectors (Choi & Olivet et al. Nat Commun. 2019)

    pYN2H-LEU-N1
    pYN2H-LEU-C1
    pYN2H-TRP-N2
    pYN2H-TRP-C2

## How to use it

Replace input.csv with a list of CCSB clones (each line one ID, e.g. CCSB_14339) and run the script.If the ORF you want to generate a vector map of is not in one of the human ORFeome banks, you can also give a name followed by the ORF sequence into the input.csv.
You can then choose (1-13) which vector maps to generate.

## Authors

* Christopher Secker
    
## License

This project is licensed under the GPLv3 license - see LICENSE file for details
