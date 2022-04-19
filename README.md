# DoubleCha
That failed - so we try the reverse patterns.     ReDim $aDoubleChar[931]     $aDoubleChar[0] = 930      For $i = 466 To $aDoubleChar[0]         $sDelim = _StringReverse($aDoubleChar[$i -465])         If Not StringInStr($sTest, $sDelim, 1) Then             Return $sDelim         Else             $arDoubleCha[$i] = $sDelim ; Needed for the next stage.         EndIf     Next
