# MusicProject

Note to examine:

- Data class imbalance (Pop-rock accounted for 50% of all the class)
- Data examine:
    + Column MFCC mean1-4 to remove
    + Chroma seems to be normalized already
    + Column Rhythm 24 not to be taken into account and look for values 1.066 (?)
    + Column MFCC_Min_1 seems to have a lot missing variables  (value = 0)
