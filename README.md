# Hottest100 - READ ME
A Challenge/Drinking Game For TripleJ Hottest 100.
--------------------------------------------------

General Information:
--------------------
This program was developed in Visual Basic and .NET and if you would like to make changes I would recommend using VS 2019, you can DM my reddit: u/CharasmaticWhenTipsy if you have any questions.

Please read this entire file before DM'ing me. It contains a lot of vital information to how to use it properly!

Legal Disclaimer:
-----------
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Installation Instructions:
--------------------------

1. Download the repository and extract the zip file (if required).

2. Run the "setup.exe" file which will install the program (This may require Administrator level permissions. 
(Note: As far as I am aware this software will only work on Win10, potentially other distributions of Windows. Given it is a .Net form it will not work on MacOS or Linux AFAIK).
(Note II: You may need to give Administrator permission/network access, this software requires an active internet conenction to use).

3. The program should launch automatically after the setup runs, if not run the application launcher or just run setup again.

Usage/Setup Instructions:
-------------------

There are two text files which are compiled as DEPLOY files contianed within the instillation directory at this location, they should be editied so you can input yours and your friends votes and change the challenges for each song: 

<Root Directory>\Application Files\Hottest 100\bin\Debug\txt

The file names are:

1: Challenges.txt.deploy
2: Votes.txt.deploy

These can be edited with a standard text editor. I reccommend Notepad++ (Free). They will both need to be edited for your personal use. 

These files must contain a specific order of information for the program to work. This information is listed below.

Run Time:
---------
To start the program hit the "H100" button in the top left hand corner of the screen, I reccomend setting the program to full screen.

If the prgoram crashes or fucks up you can restart it and click "Skip Songs" and enter the current number in the hottest 100 that is playing and it will catch you back up on the challenges.


Votes.txt:
----------

'Votes.txt.deploy' will store yours and your friends votes for the Hottest 100.

The text file should be in the following format:

The First Line is special and contains the total number of songs voted for as an integer i.e "67": <Total Number of Songs Voted For>
If the same song is voted for twice it counts as one song. All of this information is catagorrised by song not by votes.

All remaining lines follow this format:
<Song Name>
<Total Number of Votes For This Song>
<Name of First Person Who Voted For The Song>
<Name of Second Person Who voted For The Song>
<Etc..>

Here is an example of what it looks like:
All Day
2
Nick
Ryan

This then repeats for however many number of songs you have which is denoted by the first line in the text file.

Here's an example of what a short version of the whole file put together looks like:
4 			- Total Number of Songs
All Day 		- Name of Song #1
2 			- Number Of Votes For Song above this line.
Nick 			- Name #1 Who voted for this song.
Ryan 			- Name #2 ...
Toasty
1
Ryan
The Best
1
Nick
Song #2
5
Ryan
Billy
Ally
YAMUM
Toby

There is a bigger example of this in the Votes.txt file in the directory, which is what I used last year.


Challenges.txt
--------------

This file will contian the challenges that each song number is. The way my friends and I use this program is that you only do the challenge if you voted for the song at this particular position.
If that doesn't make sense just fill in your votes in Votes.txt and it will make sense once you run the program for a couple of songs.

This file's format is quite simple. It should count down as follows:

100 - Take 1 sip
99 - Give out 1 sip
98 - Lick a bar of soap (unless you’re Tommy in which case eat the whole damn thing)
97 - Put some drink in a king's cup
96 - Take 1 sip
95 - Find something in the kitchen, and put it in the kitchen cup
94 - Give out 2 sips
93 - Lick a tyre
92 - Drink half a cup of punch
91 - Do 20 pushups
90 - Take 2 sips 

This continues all the way down to 1. These challenges are just examples. The file included is the one we used from last year. I'll be updating that based on what we found worked and didn't but it's all a matter of preference and getting creative :)
Check the file with a text editor if you need an example of what the file looks like completed and then edit it as you wish!
