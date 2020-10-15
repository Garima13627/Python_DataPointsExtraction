# Python_DataPointsExtraction

This excercise is a simple program that reads a text file of a specified format (for example json) and outputs specified data points to a text file ( json)

Sample Problem for the code:

From a given input json file, First read the input and then extract 3 kinds of information from each paragrpah:
-duration if there are atleast two dates
  Integer-time duration in days (inclusive of the given dates). If unknown or uncomputable, then 0

-whether the subject of the text identifies as female 
  String - "female" or "other"

-sentiment expressed in the text
  String - "positive", "negative", "mixed" or "unknown"
  
Once these data are extracted , the data should be written out to a file .

Assumptions:
For time duration, the format MM/DD/YYYY is assumed to be correct
For female identification, look for female identifying pronouns : she, her, hers
For sentiment, look for the following keywords:
  Positive sentiments: Happy, Glad, Jubilant, Satisfied
  Negative sentiments: Sad, Disappointed,Angry,Frustated
  
