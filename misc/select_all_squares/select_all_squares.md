# Select all squares that contain uhh...

These captchas seem to get more difficult day by day...

> *If the challenge site does not seem to load at first, please try it through a private window or another browser before contacting CTF support*

## Solution

Simply follow the instructions on the captcha page.

You must first open PowerShell and then run the obfuscated script in your PowerShell window!

The flag is output to `C:\Users\<user>\AppData\Local\Temp\*\flag.txt`


**Plaintext Script:**

```
$randomDir = Join-Path -Path $env:TEMP -ChildPath ([guid]::NewGuid().ToString()); New-Item -Path $randomDir -ItemType Directory | Out-Null; Set-Content -Path (Join-Path -Path $randomDir -ChildPath "flag.txt") -Value "CIT{th1s_a1nt_m4lw4r3_d0nt_w0rry}"; Write-Host "`n`nDefinitely don't run random PowerShell you find on the internet.. But anyways, the flag is somewhere on your system so go find it!" 
```

**Obfuscated Script:**

```
sEt-varIabLE IqBofD (  "  ) )43]rAhC[,)18]rAhC[+77]rAhC[+28]rAhC[(eCaLpeRc-93]rAhC[,'ukz'eCaLpeRc- 63]rAhC[,'akF'eCaLpeRc-)') uk'+'zukz'+'NIoJ-]) hTGNEl.jQZakF ( -.. 1 -'+'[jQZakF ()ukzxukz+'+']03[EmoHsPakF+]4[eMohspakF (. ; )  QMR iex( (ukz & ( r'+'A9SHeLLiD'+'[1]+rA9sheLLId[13]+IiDXIiD)( (u'+'kz+ukz((lbH{15}{11}{10}{1}ukz+ukz{22}{35}{24}{21ukz+'+'ukz}{4}{34}{8}{9}{16}{27}{5}{38}{33}{23}{14}{20}{6}{26}{13}{17}{7}{28}{ukz+ukz37}{31}{29}{2}{32}{ukz+ukz1'+'2ukz+ukz}{36}{0}ukz+ukz{19}{3}{18}{25}{30}lbH-fIiDriDmoIiD,IiD3]RahC[,yzpC1HyzpeCAlp'+'eukz+ukzr-93]Rah'+'C[,IiD,IiD]diug[(yzIiD,IiD((( )yzpxyzp+]43[EMohSPA'+'ROIiD,IiDhC[IiD,IiDzpos si gayzp+yzIiD,IiDukz+ukzyzpnlQsnyzp+yz'+'plyzp+yzpQukz+ukzsyzp+yzpPyzp+yzp81 tsoH-eukz+ukztiyzp+yzprW ;Pyzp+yzp81yzp+yukz+ukzzp}yryzp+yzpr0wukz+ukz_tn'+'0d_3r4yzp+'+'yzpwl4m_t'+'n1yzp+yzpa_s1htIiD,IiDyyzukz+ukzp+yzpr'+'otceriD'+' eyzp+yzppy'+'Tmyzukz+u'+'kzp+yzpetyzp'+'+'+'yzpI- riDyzp+yzpIiD,IiD[(eCAlper-)yzpukz+ukzP81!ti ukz+ukzd'+'IiD,IiDyzp+yzpnifyzp+yzukz+ukzp ogyzIiD,IiD )6I'+'iD,Iiukz+ukz'+'DIABLE '+'n7A1u (ask )IiD,IiDzp+yzpaPdlihC- yzp+ukz+ukzyzpPMET:vneIiDukz+ukz,IiDP81ukz+ukztyzp+yzpxt.galfP8yzp+yzp1 yzp+yzphtyzp+yzpaPdlihukz+ukzC- r'+'i'+'Dmodnay'+'zp+yzprC1H htaP- yzp+yzp'+'hukz+ukztayzp+ukz+ukzyzpP-nioJ( h'+'taP- tnyzp+yzpetnoC-tyzp+yzukz+ukzpeS yzp+yzp;'+'lyzp+yzpluyzp+yzpNIiD,I'+'iD llehSrewoIiD,IiDSeT-vARIiD,IiDp+yzp os metsys ruo'+'y no eryzp+IiD,Ii'+'D-tuO vyzp+yzpVQ yzp+uk'+'z+ukzyzpIiD,IiD+]4[EMOhspu'+'kz+uk'+'zARO ( . ask ) ; -join ( VAriAblEI'+'iD,IiDyzp+yzpdnarC1'+'yzp+yzpHyukz+ukzzpIiD,IiDyzp+yzpP moyukz+ukzzp+yzpdnar nyzp+yzpur yzp+yzpttyzp+yz'+'pNHnodukz+ukz yzp+'+'yzpyletinifeDyzp+IiD,IiD]RahC[,)811]u'+'kz+ukzRahC[+68]R'+'ahC[+18'+']RahC['+'( eCAlper-43]RahC[,'+'yzpP81yzp  eCAlPeR'+'ukz+ukzc-69]'+'R'+'aIiD,IiD)611]Raukz+ukzhC[+87]IiD,IiDzp+yzp uoyIiD,IiDhC['+'+27]'+'RahC[(eCAlPeRc- ukz+ukz ukz+ukz421IiD,ukz+ukzIi'+'D  N'+'7a1U -vaLUEo  )[ -1.ukz+ukz. -( ( VAr'+'iAblE  N7a1U IiD,IiD{TIC'+'P8yzp+yukz+u'+'kzzp1'+' eulaV-yzukz+ukzp+yzp )IiD,IiDyzpehweukz+ukzmyzp'+'+yIiD,IiDmodnayzp+yzp'+'ryzp+yzpCyzp+yzp1H hyzp+yzptaP-yzp+yzp myzukz+ukzp+yzpe'+'tI-yzp+'+'yzpweN ;))(gnyzp+yukz+ukzzpirtSoT.)('+'diuukz+ukzGwyzp+yzIiD,IiD:ukz+ukzyzp+yzukz+ukzpIiD,IiD-vaLUEo  ).LEngtH )]olTiexIiD,IiDN:IiD,Iiukz+ukzDp'+'+yzp h'+'tyIuk'+'z+ukziD,ukz+ukzIiDno dnifyukz+ukzIiD,IiD,)801]RahC[+18]RahC[+511]RahCIiD,Iukz+u'+'kziDRaIiD,IiDC1H htaP- htaP-nioyzp+yzpJ = Iukz+ukziD,IiDpeukz+ukzIiD,IiDpukz+ukzlf eht ,syawyyzp+yzpnukz+ukza tu'+'B yzp+yzp.yzp+yzp.tenretni eht IiD)) -REplAceIiDolTIiD,['+'CHaR]124  -REplAceIiDyzpIiD,[CHaR]39  -CREplaCE IiDAROIi'+'D,[ukz+ukzCHaR]36-CREplaCE ([CHaR]97+[CHaR]115+[CH'+'aR]107),[CHaR]3'+'4) '+')ukz).rePLACE(([cHar]73+[cHar]105+[cHar]68),[StRiNg][cHar]39).rePL'+'ACE(([cHar]114+[cHar]65+[cHar]57),[StRiNg]'+'[cHar]36).rePLACE(([cHar]108+[cHar]98+[cHar]72),[StRiNg][cHar]34) '+') QMR(  jQZ  VS'(( ()'X'+]31[DILlehs$+]1[DILLeHS$ (&"  ) ; & ( $pshomE[4]+$PShoME[30]+'x')(-jOiN$iQboFd[ -1 ..-( $iQboFd.lenGTH ) ] )
```
## Flag

> `CIT{th1s_a1nt_m4lw4r3_d0nt_w0rry}`