#1. 
INITIALIZE inString to empty
INITIALIZE tempVariable to inString
WHILE inString has less than 5 characters

     GET one character INPUT

     ADD INPUT to inString 

END WHILE

FOR position first element to (length of inString - 1)
     SET TempVariable to element in inString 
     //tempVariable='c'
     FOR EACH element in tempVariable
          IF element in tempVariable > element in inString
                PUT element inString at the end of tempVariable
           ELSE 
                FOR EACH element in TempVariable
                     IF element in inString > element in tempVariable
                      PUT element in inString before last element in tempVariable
               NEXT
      NEXT
NEXT



