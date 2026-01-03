1. Start
2. Set previousScore = -1, trend = "Stable"
3. For each score in StudentScores do
4.     If previousScore != -1 then
5.         If score > previousScore then trend = "Improving"
6.         Else trend = "Declining"
7.     End If
8.     previousScore = score
9. End For
10. Display trend
11. End


