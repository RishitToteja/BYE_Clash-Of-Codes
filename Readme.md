# VIBE- Find your match
## P.S.- PROFILE SCORING AND FETCHING RANDOM PROFILES

## TEAM NAME- BYE

## TEAM MEMBERS-
* Abhisht Dixit
* Gunraj Singh
* Ishita Jain
* Rishit Toteja

## INTRODUCTION-
There are two parts to the problem statement-
1) Profile scoring- For this we are going to evaluate each profile based on different parameters like verified, if 100% completion, number of users
liked him/her, number of matches received, paid subscription or a free profile, verified user or not, number of likes done vs received, dislike
by likes ratio performed and received, etc. This evaluation wold be done based on a scoring function deveoped by us rating the profile on the scale of 1 to 5 stars.

2) Fetching appropriate profiles for the users- For this we will use our rating system to get similar profiles. This is done to make sure all users don't end up seeing the same person. 100 latest accounts, are taken into consideration, shuffling them and showing them to users. So, latest profiles are more visible (Latest as in top 100 latest profiles). Also, for the first 24 hours, free accounts should be given a bias so that more people could view them and the chances for free to pro subscription increases. Also people getting zero or low number of matches should be shown more than people already receiving matches. This is to allow all people to get a match. These should be done according to a scoring mechanism so that we don't end up making too many db calls for each case. End goal is to create a function which takes your profile as an input and sends 10 profiles.




