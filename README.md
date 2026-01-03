Set previousScore = -1
Set trend = "Stable"
For each score in StudentScores do
    If previousScore != -1 then
        If score > previousScore then
            trend = "Improving"
        Else
            trend = "Declining"
        End If
    End If
    previousScore = score
End For

