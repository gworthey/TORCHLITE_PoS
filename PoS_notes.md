# Notes, documentation links, and sample data for multilingual PoS tags

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
 - Arabic: https://www.sketchengine.eu/stanford-arabic-parser-tagset/
 - Chinese: https://verbs.colorado.edu/chinese/posguide.3rd.ch.pdf
 - French: http://www.llf.cnrs.fr/Gens/Abeille/French-Treebank-fr.php   https://stackoverflow.com/questions/27513185/simplifying-the-french-pos-tag-set-with-nltk
 - German: http://www.sfs.uni-tuebingen.de/resources/stts-1999.pdf
 - Spanish: https://melaniewalsh.github.io/Intro-Cultural-Analytics/05-Text-Analysis/Multilingual/Spanish/03-POS-Keywords-Spanish.html
 
### Proposed grouping and mapping of non-English POS tags for our widget 
 - [PoS_tagsets.txt](https://github.com/gworthey/TORCHLITE_PoS/blob/main/PoS_tagsets.txt)

### Sample non-English HTIDs:
*Arabic:*
- mdp.39015064570461
- mdp.39015024523972
- mdp.39015048456746
- mdp.39015069916222	
- mdp.39015065641949	
- mdp.39015008029129	
- mdp.39015070404531	
- mdp.39015070404838	
- mdp.39015055122207	
- mdp.39015070404846

*Chinese:*
- uiug.30112031277228
- uc1.$b490300
- uc1.b5199346
- osu.32435020686291
- uiug.30112031284760
- uc1.31210003722608
- osu.32435022461701
- osu.32435022461693
- osu.32435057619587
- osu.32435068589571

*French:*
- mdp.49015000787391
- mdp.39015070155141	
- mdp.39015074215453	
- mdp.39015065209051	
- mdp.39015015802484	
- mdp.39015028372665	
- mdp.39015030781465	
- mdp.39015030024478	
- mdp.39015002963174	
- mdp.39015058538961

*German:*
- mdp.39015024518378
- mdp.39015026241839
- mdp.39015009452197	
- mdp.39015062271641	
- mdp.39015069898289	
- mdp.39015058537195	
- mdp.39015016444922	
- mdp.39015026989692	
- hvd.32044077954949	
- mdp.39015026239783	

*Spanish:*
- hvd.hwjqd8
- mdp.39015029907493 
- mdp.39015041448328	
- nyp.33433082126172	
- miun.abk1111.0001.001	
- mdp.39015027224768	
- mdp.39015027224768	
- mdp.39015026445380	
- miun.ack4656.0001.001	
- mdp.39015031060885

User Notes
Spanish language distributions are not out of 100% (unknown error- future work)
