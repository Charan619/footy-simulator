# footy-simulator
Football season simulator using cpp


            TODO:
--Tactical Settings--
Attack style and Defence style-1,2,3(1 is least aggressive)
if AS of team 1 and DS of team 2:
-are equal, no modifiers apply
-1 and 3, *1.4 mod attack stats
-2 and 3, *1.2 mod att stats
-1 and 2, *1.2 mod att stats
-3 and 2, *1.2 mod att stats
-2 and 1, *1.2 att
-3 and 1, *1.4 att

AW of team 1 and DW of team 2:(1 is widest)
-both 1 or 3 ,*1.4 def stats
-2,3, *1.2 def
-2,1, *1.2 def
-1,3, no change
-3,1, no change
-1,2, *1.2
-3,2, *1.2
-both 2,*1.3 def


-Loading game(done)
-checking if manager name is unique(done)
-player database filling in notepad
-adding tact settings and changing starting 11(checking if goalie is also in lineup)
-time delay setting while simming match
-ui/gui?
-multiple seasons?
