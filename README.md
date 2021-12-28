# MoM-Converter

BIG THANKS TO WATERKH FOR PROVIDING DOCUMENTATION ON CHART FILES AND CREATING RE:CHART TOOL


MoMConverter will take StepMania(.sm) or Osu!(.osu) files and convert it into a format (almost)
usable in Melody of Memory. Converted files will need to run through WaterKH's Re:Chart tool
in a few different steps


Converter created by Limen123
Converter is still in VERY EARLY STAGES and will have LOTS OF BUGS AND ISSUES
----------------------------------------------------------------------------------------------

BEFORE YOU RUN:
 - Open desired chart in Re:Chart
 - Clear chart and recompile
	- IF DOING BOSS CHART, CLOSE RECHART AND REPEAT THIS STEP A SECOND TIME

 - If you are converting a .osu(NOT TAIKO OR MANIA) file, there should not be anymore required steps
   before running the program.

 - If you are converting a .sm file, please make sure you have edited the contents of the .sm file
   to ONLY have your desired difficulty. Example snippet at bottom of readme

----------------------------------------------------------------------------------------------

RUN THE PROGRAM
 - ENTER REQUIRED FILES. SELECT THE SAME SONG TYPE AS THE ORIGINAL CHART

 - YOU MUST NOW OPEN THE NEW FILE IN RECHART AND RECOMPILE AT LEAST ONCE FOR IT TO
   RUN PROPERLY IN GAME. CURRENT FILESIZE LIMIT IS 256KB. IF LARGER, THE RECHART FIX WILL NOT WORK

----------------------------------------------------------------------------------------------
An example of what a .sm file looks like below:


#TITLE:;

#BPMS:0.000=200.000;

//--------------- dance-single -  ----------------

#NOTES:

dance-single:

:

Beginner:

1:

0,0,0,0,0:

0000

0000

0000

0000

,

1100

0010

0001

0010

0100

1000

0100

0010

;




You will want to copy from #NOTES to the semicolon at the bottom of the chart. Keep all of
the header information(everything with a #) but get rid of the rest of the charts while
only keeping the desired chart. Save the edited stepchart somewhere and run the program
using the newly	edited file.
