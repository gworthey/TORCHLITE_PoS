# TORCHLITE_PoS
HTRC TORCHLITE Hackathon group working on Part of Speech

## Coding plan
- EF-API call
- Function to aggregate PoS counts
- D3 to visualize

## Sample data
### clean HTIDs: 
 - mdp.39015016452230
 - mdp.49015001017970 (Gertrude Stein)
### unclean HTIDs:
 - uc2.ark:/13960/t4sj1b439
 - dul1.ark:/13960/t4wh8z13n
### sample API call: https://htrc.stoplight.io/docs/ef-api/fafb232808611-get-ef-data-for-a-volume-by-volume-id

## Non-English work
### Non-English POS tagsets (need to confirm that these are actually what's being used in EF)
 - Arabic: ?
 - Chinese: https://verbs.colorado.edu/chinese/posguide.3rd.ch.pdf
 - French: http://www.llf.cnrs.fr/Gens/Abeille/French-Treebank-fr.php
 - German: http://www.sfs.uni-tuebingen.de/resources/stts-1999.pdf
 - Spanish: https://melaniewalsh.github.io/Intro-Cultural-Analytics/05-Text-Analysis/Multilingual/Spanish/03-POS-Keywords-Spanish.html
 
### Proposed grouping and mapping of non-English POS tags for our widget 
 - [PoS_tagsets.txt](https://github.com/gworthey/TORCHLITE_PoS/blob/main/PoS_tagsets.txt)

### Sample non-English HTIDs:
 - Arabic: mdp.39015064570461
 - Chinese: uiug.30112031277228
 - French: mdp.49015000787391
 - German: mdp.39015024518378
 - Spanish: hvd.hwjqd8
