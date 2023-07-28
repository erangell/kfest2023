# kfest2023
Code for Kansasfest 2023: FujiApple Tic Tac Dough

- INTBSYS_TTD2023.po has the Client and Server to run the game on Apple ][ machines with Fujinet installed.
- INTBSYS_TTDWORK.po has code that was used in the creation of the game, but not needed to run the game.
- INTBSYS_FUN.po has Integer Basic programs that now run under Prodos.
- FN-Tic-Tac-Dough.atr is an Atari disk image which boots to a Basic program that runs a TTD server.
- TICTACDRAGON.dsk has the lo-res art entry from Kansasfest 2022 with an update to play the music with all 5 timbres.

To generate questions for the game, enter the following prompt into ChatGPT3:

Please generate 10 different game boards each consisting of 9 trivia questions in 9 unique categories that could be used in a game of Tic Tac Dough in JSON format.  The outermost objects should be named "game".  The 9 trivia questions for each game should have field names: category, question, answer

Special thanks to inexorabletash for adding the Programmer's Aid Music routines to INTBASIC.SYSTEM
- https://github.com/a2stuff/intbasic/issues/12
- https://www.callapple.org/vintage-apple-computers/apple-ii/intbasic-system-0-9-for-the-apple-ii-released/

Rules for Tic Tac Dough game show can be found here:
- https://en.wikipedia.org/wiki/Tic-Tac-Dough

Sample episodes of the game show can be found here:
- https://www.youtube.com/@gbgameshows/search?query=tic%20tac%20dough

Youtube Playlist for this project:
- https://www.youtube.com/watch?v=n10ZzsD5x4E&list=PLOW4_Hp8_910b5OBxWW4ZuY0Fnz8SmFWE

Youtube Playlist of videos about #Fujinet:
- https://www.youtube.com/watch?v=58YSpwc9OZ0&list=PLOW4_Hp8_911MfGisFSE2-PmqPhco1X1q

Test Plan (Google Spreadsheet)
- https://docs.google.com/spreadsheets/d/1buVD_l5Ehudc-TbOcdZdjQRgrE3htOXg/edit?usp=sharing&ouid=117510875400639877571&rtpof=true&sd=true

Additional links to work by Bob Bishop:
- Bob Bishop talking about his work on Tic Tac Dough: https://www.youtube.com/watch?v=FlsHGmijFP0&t=2136s
- https://www.apple2history.org/spotlight/bobbishop/
- Em Maginnis interviewed Bob Bishop in 2009: https://archive.org/details/BobBishopInterview-2009-04-22
- Bob Bishop's radio show: https://archive.org/details/the-thinking-machine-bishop-woz-interview
- KSCO Santa Cruz obituary for Bob: http://www.ksco.com/bob-bishop-mr-logic-obit-09-29-14-16-00-s-s/
- Bob's language: SIMPLE http://web.archive.org/web/20130317194809/http://www.simplecodeworks.com/website.html
  
