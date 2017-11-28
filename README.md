#Source 1: Slides from first few lectures
#Source 2: http://www.techteachers.co.za/2015/07/multiple-choice-quiz-using-python/

#================
#= Introduction =
#================

name = input('Your name? ')
print('\nWell hello there, ' + name + '. Welcome to this little trivia game. Prepare yourself.\n')

print('You get 30 questions, and each has four answers to choose from.\n')
print('These questions are random and do not relate to one specific topic of interest.\n')
print('You choose the answer you think is correct and the score depends on how many you get right.\n')

Continue = input('Press the Enter key to continue.')

print('\n====================================================================\n')

print('Here are some important things to remember.\n\n')
print('Note 1: You do not have to input the whole answer. Just the letter that corresponds to it.\n')
print('Note 2: The letter must be capitalized. Lowercase letters are unacceptable.\n')
print('Note 3: You do not have to keep track of your score. We will do that for you. *Raises fist*\n')
print('Note 4: Good luck! :)\n')

Continue = input('Press the Enter key to continue.')

print('\n====================================================================\n')

#===============================
#= Keeping track of your score =
#===============================
points = 0
points = int(points) #This is highly important to remember

#==================
#= First question =
#==================
print('Okay. First question: Which country hosted the 1952 summer Olympic Games?\n')

print('A) Finland\n')
print('B) Germany\n')
print('C) France\n')
print('D) Spain\n\n')

Response_q01 = input('')

Answer_q01 = "A"

if(Response_q01 == Answer_q01):
	points = points + 1

print('\n====================================================================\n')

#===================
#= Second question =
#===================
print('Second question: What was the name of the dog on the TV show "The Jetsons"?\n')

print('A) Comet\n')
print('B) Astro\n')
print('C) Spike\n')
print('D) Pluto\n\n')

Response_q02 = input('')

Answer_q02 = "B"

if(Response_q02 == Answer_q02):
	points = points + 1

print('\n====================================================================\n')

#==================
#= Third question =
#==================

print('Third question: What year did Wayne Gretzky retire from professional hockey?\n')

print('A) 1997\n')
print('B) 2000\n')
print('C) 1998\n')
print('D) 1999\n\n')

Response_q03 = input('')

Answer_q03 = "D"

if(Response_q03 == Answer_q03):
	points = points + 1

print('\n====================================================================\n')

#===================
#= Fourth question =
#===================

print('Fourth question: What Andrew Lloyd Webber musical ran from 1982 to 2000?\n')

print('A) Cats\n')
print('B) Les Miserables\n')
print('C) Rent\n')
print('D) The Rocky Horror Show\n\n')

Response_q04 = input('')

Answer_q04 = "A"

if(Response_q04 == Answer_q04):
	points = points + 1

print('\n====================================================================\n')

#==================
#= Fifth question =
#==================

print('Fifth question: Which country lies between Switzerland and Austria?\n')

print('A) Germany\n')
print('B) Poland\n')
print('C) Liechtenstein\n')
print('D) Czechoslovakia\n\n')

Response_q05 = input('')

Answer_q05 = "C"

if(Response_q05 == Answer_q05):
	points = points + 1

print('\n====================================================================\n')

#==================
#= Sixth question =
#==================

print('Sixth question: What city is home to the Rose Tower?\n')

print('A) Toronto\n')
print('B) Dubai\n')
print('C) Paris\n')
print('D) London\n\n')

Response_q06 = input('')

Answer_q06 = "B"

if(Response_q06 == Answer_q06):
	points = points + 1

print('\n====================================================================\n')

#====================
#= Seventh question =
#====================

print('Seventh question: What device was Alexander Graham Bell working on that led him to invent the telephone?\n')

print('A) Telegram\n')
print('B) Grappling hook\n')
print('C) Cable wires\n')
print('D) Hearing aid\n\n')

Response_q07 = input('')

Answer_q07 = "D"

if(Response_q07 == Answer_q07):
	points = points + 1

print('\n====================================================================\n')

#===================
#= Eighth question =
#===================

print('Eighth question: What band recorded the album "A Night at the Opera"?\n')

print('A) The Who\n')
print('B) The Beatles\n')
print('C) Queen\n')
print('D) Black Sabbath\n\n')

Response_q08 = input('')

Answer_q08 = "C"

if(Response_q08 == Answer_q08):
	points = points + 1

print('\n====================================================================\n')

#==================
#= Ninth question =
#==================

print('Ninth question: What is the atomic number of gold?\n')

print('A) 48\n')
print('B) 79\n')
print('C) 36\n')
print('D) 90\n\n')

Response_q09 = input('')

Answer_q09 = "B"

if(Response_q09 == Answer_q09):
	points = points + 1

print('\n====================================================================\n')

#==================
#= Tenth question =
#==================

print('Tenth question: Which Australian animl has unique fingerprints?\n')

print('A) Kangaroo\n')
print('B) Sloth\n')
print('C) Koala\n')
print('D) Kiwi\n\n')

Response_q10 = input('')

Answer_q10 = "C"

if(Response_q10 == Answer_q10):
	points = points + 1

print('\nOne-third of the way there. :)')

print('\n====================================================================\n')

#=====================
#= Eleventh question =
#=====================

print('Eleventh question: Hellas is the local name for which country?\n')

print('A) Helsinki\n')
print('B) Greece\n')
print('C) Italy\n')
print('D) Poland\n\n')

Response_q11 = input('')

Answer_q11 = "B"

if(Response_q11 == Answer_q11):
	points = points + 1

print('\n====================================================================\n')

#====================
#= Twelfth question =
#====================

print('Twelfth question: What is the name for a baby alligator?\n')

print('A) Calf\n')
print('B) Pod\n')
print('C) Alligator\n')
print('D) Hatchling\n\n')

Response_q12 = input('')

Answer_q12 = "D"

if(Response_q12 == Answer_q12):
	points = points + 1

print('\n====================================================================\n')

#=======================
#= Thirteenth question =
#=======================

print('Thirteenth question: What is the most spoken language in the world?\n')

print('A) English\n')
print('B) Spanish\n')
print('C) French\n')
print('D) Chinese\n\n')

Response_q13 = input('')

Answer_q13 = "D"

if(Response_q13 == Answer_q13):
	points = points + 1

print('\n====================================================================\n')

#=======================
#= Fourteenth question =
#=======================

print('Fourteenth question: What was the first planet to be discovered using the telescope in 1781?\n')

print('A) Pluto\n')
print('B) Uranus\n')
print('C) Jupiter\n')
print('D) Mars\n\n')

Response_q14 = input('')

Answer_q14 = "B"

if(Response_q14 == Answer_q14):
	points = points + 1

print('\n====================================================================\n')

#======================
#= Fifteenth question =
#======================

print('Fifteenth question: How many U.S. states border the Gulf of Mexico?\n')

print('A) Three\n')
print('B) Four\n')
print('C) Five\n')
print('D) Six\n\n')

Response_q15 = input('')

Answer_q15 = "C"

if(Response_q15 == Answer_q15):
	points = points + 1

print('\nHalfway there. You can do this.')

print('\n====================================================================\n')

#======================
#= Sixteenth question =
#======================

print('Sixteenth question: Which record label did Michael Jackson first record his music for?\n')

print('A) Motown\n')
print('B) Atlantic\n')
print('C) Warner Music\n')
print('D) Sony\n\n')

Response_q16 = input('')

Answer_q16 = "A"

if(Response_q16 == Answer_q16):
	points = points + 1

print('\n====================================================================\n')

#========================
#= Seventeenth question =
#========================

print('Seventeenth question: With what di  the ancient Romans dye their hair?\n')

print('A) White paint\n')
print('B) Oil\n')
print('C) Bird poop\n')
print('D) Mars\n\n')

Response_q17 = input('')

Answer_q17 = "C"

if(Response_q17 == Answer_q17):
	points = points + 1

print('\n====================================================================\n')

#=======================
#= Eighteenth question =
#=======================

print('Eighteenth question: What does the C stand for in LCD?\n')

print('A) Clear\n')
print('B) Crystal\n')
print('C) Colored\n')
print('D) Ceramic\n\n')

Response_q18 = input('')

Answer_q18 = "B"

if(Response_q18 == Answer_q18):
	points = points + 1

print('\n====================================================================\n')

#=======================
#= Nineteenth question =
#=======================

print('Nineteenth question: Which nail grows fastest?\n')

print('A) Middle\n')
print('B) Index\n')
print('C) Ring\n')
print('D) Pinky\n\n')

Response_q19 = input('')

Answer_q19 = "A"

if(Response_q19 == Answer_q19):
	points = points + 1

print('\n====================================================================\n')

#======================
#= Twentieth question =
#======================

print('Twentieth question: Where was Christopher Columbus born?\n')

print('A) Italy\n')
print('B) Spain\n')
print('C) Sicily\n')
print('D) Genoa\n\n')

Response_q20 = input('')

Answer_q20 = "D"

if(Response_q20 == Answer_q20):
	points = points + 1

print('\nTwo-thirds of the way done. Keep it up. :D')

print('\n====================================================================\n')

#=========================
#= Twenty-first question =
#=========================

print('Twenty-first question: Name the director of the Lord of the Rings trilogy.\n')

print('A) George Lucas\n')
print('B) Steven Spielberg\n')
print('C) Peter Jackson\n')
print('D) Spike Lee\n\n')

Response_q21 = input('')

Answer_q21 = "C"

if(Response_q21 == Answer_q21):
	points = points + 1

print('\n====================================================================\n')

#==========================
#= Twenty-second question =
#==========================

print('Twenty-second question: How many valves does a trumpet have?\n')

print('A) 3\n')
print('B) 4\n')
print('C) 5\n')
print('D) 6\n\n')

Response_q22 = input('')

Answer_q22 = "A"

if(Response_q22 == Answer_q22):
	points = points + 1

print('\n====================================================================\n')

#=========================
#= Twenty-third question =
#=========================

print('Twenty-third question: In 2011, which country hosted a Formula 1 race for the first time?\n')

print('A) Japan\n')
print('B) India\n')
print('C) France\n')
print('D) Italy\n\n')

Response_q23 = input('')

Answer_q23 = "B"

if(Response_q23 == Answer_q23):
	points = points + 1

print('\n====================================================================\n')

#==========================
#= Twenty-fourth question =
#==========================

print('Twenty-fourth question: Which chess peice can only move diagonally?\n')

print('A) A knight\n')
print('B) A queen\n')
print('C) A bishop\n')
print('D) A rook\n\n')

Response_q24 = input('')

Answer_q24 = "C"

if(Response_q24 == Answer_q24):
	points = points + 1

print('\n====================================================================\n')

#=========================
#= Twenty-fifth question =
#=========================

print('Twenty-fifth question: When did the Cold War end?\n')

print('A) 1989\n')
print('B) 1980\n')
print('C) 1990\n')
print('D) 1985\n\n')

Response_q25 = input('')

Answer_q25 = "A"

if(Response_q25 == Answer_q25):
	points = points + 1

print('\n====================================================================\n')

#=========================
#= Twenty-sixth question =
#=========================

print('Twenty-sixth question: What color is an orange blossom?\n')

print('A) Red\n')
print('B) White\n')
print('C) Orange\n')
print('D) Yellow\n\n')

Response_q26 = input('')

Answer_q26 = "B"

if(Response_q26 == Answer_q26):
	points = points + 1

print('\n====================================================================\n')

#===========================
#= Twenty-seventh question =
#===========================

print('Twenty-seventh question: French horns originated from which country?\n')

print('A) France\n')
print('B) Sweden\n')
print('C) Greece\n')
print('D) Germany\n\n')

Response_q27 = input('')

Answer_q27 = "D"

if(Response_q27 == Answer_q27):
	points = points + 1

print('\n====================================================================\n')

#==========================
#= Twenty-eighth question =
#==========================

print('Twenty-eighth question: Which is the strongest bone in the human body?\n')

print('A) Collarbone\n')
print('B) Skull\n')
print('C) Thighbone\n')
print('D) Spine\n\n')

Response_q28 = input('')

Answer_q28 = "C"

if(Response_q28 == Answer_q28):
	points = points + 1

print('\n====================================================================\n')

#=========================
#= Twenty-ninth question =
#=========================

print('Twenty-ninth question: In a game of 9-ball, the pool balls are placed in what shape?\n')

print('A) A triangle\n')
print('B) A square\n')
print('C) A diamond\n')
print('D) A rhombus\n\n')

Response_q29 = input('')

Answer_q29 = "C"

if(Response_q29 == Answer_q29):
	points = points + 1

print('\n====================================================================\n')

#======================
#= Thirtieth question =
#======================

print('Thirtieth question: How many canine teth are there in a normal set of human teeth?\n')

print('A) 2\n')
print('B) 4\n')
print('C) 8\n')
print('D) 16\n\n')

Response_q30 = input('')

Answer_q30 = "B"

if(Response_q30 == Answer_q30):
	points = points + 1

print('\nWe are finally done. Woo!')

print('\n====================================================================\n')

#=============
#= What now? =
#=============

print('Okay. Now that you have completed the trivia game, it is time to see how you did.\n')

print('\nYour final score: ' + str(points) + ' out of 30!\n')

#=======================
#= Results of the game =
#=======================

if(21 <= points <= 30):
	print('Look at you. You deserve an award. Unfortunately, we do not have one. :(\n')

if(11 <= points <= 20):
	print('Not too bad. You could have done better, though.\n')

if(1 <= points <= 10):
	print('Well. I have no words of motivation for you at the moment. :/\n')

if(points == 0):
	print('There is no way you got 0 points. How Sway???')

Continue = input('\n\nPress the Enter key to continue.')

#================================
#= Looking back at your answers =
#================================

print('\n====================================================================\n')

print('Let us look back at your answers. We will compare it to the correct ones.')

#===================================================================
#= This part is kind of simple. It tells you what your answer was, =
#= then shows you the correct answer. If the answers are the same, =
#= the program gives you a pat on the back. Otherwise, it tells    =
#= wishes you better luck next time.                               =
#===================================================================

print('\n====================================================================\n')

print('For the first question, you put ' + Response_q01 + ' as your answer.\n')
print('The correct answer: ' + Answer_q01 + '.\n')

if(Response_q01 == Answer_q01):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the second question, you put ' + Response_q02 + ' as your answer.\n')
print('The correct answer: ' + Answer_q02 + '.\n')

if(Response_q02 == Answer_q02):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the third question, you put ' + Response_q03 + ' as your answer.\n')
print('The correct answer: ' + Answer_q03 + '.\n')

if(Response_q03 == Answer_q03):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the fourth question, you put ' + Response_q04 + ' as your answer.\n')
print('The correct answer: ' + Answer_q04 + '.\n')

if(Response_q04 == Answer_q04):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the fifth question, you put ' + Response_q05 + ' as your answer.\n')
print('The correct answer: ' + Answer_q05 + '.\n')

if(Response_q05 == Answer_q05):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the sixth question, you put ' + Response_q06 + ' as your answer.\n')
print('The correct answer: ' + Answer_q06 + '.\n')

if(Response_q06 == Answer_q06):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the seventh question, you put ' + Response_q07 + ' as your answer.\n')
print('The correct answer: ' + Answer_q07 + '.\n')

if(Response_q07 == Answer_q07):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the eighth question, you put ' + Response_q08 + ' as your answer.\n')
print('The correct answer: ' + Answer_q08 + '.\n')

if(Response_q08 == Answer_q08):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the ninth question, you put ' + Response_q09 + ' as your answer.\n')
print('The correct answer: ' + Answer_q09 + '.\n')

if(Response_q09 == Answer_q09):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the tenth question, you put ' + Response_q10 + ' as your answer.\n')
print('The correct answer: ' + Answer_q10 + '.\n')

if(Response_q10 == Answer_q10):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the eleventh question, you put ' + Response_q11 + ' as your answer.\n')
print('The correct answer: ' + Answer_q11 + '.\n')

if(Response_q11 == Answer_q11):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twelfth question, you put ' + Response_q12 + ' as your answer.\n')
print('The correct answer: ' + Answer_q12 + '.\n')

if(Response_q12 == Answer_q12):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the thirteeth question, you put ' + Response_q13 + ' as your answer.\n')
print('The correct answer: ' + Answer_q13 + '.\n')

if(Response_q13 == Answer_q13):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the fourteenth question, you put ' + Response_q14 + ' as your answer.\n')
print('The correct answer: ' + Answer_q14 + '.\n')

if(Response_q14 == Answer_q14):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the fifteenth question, you put ' + Response_q15 + ' as your answer.\n')
print('The correct answer: ' + Answer_q15 + '.\n')

if(Response_q15 == Answer_q15):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the sixteenth question, you put ' + Response_q16 + ' as your answer.\n')
print('The correct answer: ' + Answer_q16 + '.\n')

if(Response_q16 == Answer_q16):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the seventeenth question, you put ' + Response_q17 + ' as your answer.\n')
print('The correct answer: ' + Answer_q17 + '.\n')

if(Response_q17 == Answer_q17):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the eighteenth question, you put ' + Response_q18 + ' as your answer.\n')
print('The correct answer: ' + Answer_q18 + '.\n')

if(Response_q18 == Answer_q18):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the nineteenth question, you put ' + Response_q19 + ' as your answer.\n')
print('The correct answer: ' + Answer_q19 + '.\n')

if(Response_q19 == Answer_q19):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twentieth question, you put ' + Response_q20 + ' as your answer.\n')
print('The correct answer: ' + Answer_q20 + '.\n')

if(Response_q20 == Answer_q20):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-first question, you put ' + Response_q21 + ' as your answer.\n')
print('The correct answer: ' + Answer_q21 + '.\n')

if(Response_q21 == Answer_q21):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-second question, you put ' + Response_q22 + ' as your answer.\n')
print('The correct answer: ' + Answer_q22 + '.\n')

if(Response_q22 == Answer_q22):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-third question, you put ' + Response_q23 + ' as your answer.\n')
print('The correct answer: ' + Answer_q23 + '.\n')

if(Response_q23 == Answer_q23):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-fourth question, you put ' + Response_q24 + ' as your answer.\n')
print('The correct answer: ' + Answer_q24 + '.\n')

if(Response_q24 == Answer_q24):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-fifth question, you put ' + Response_q25 + ' as your answer.\n')
print('The correct answer: ' + Answer_q25 + '.\n')

if(Response_q25 == Answer_q25):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-sixth question, you put ' + Response_q26 + ' as your answer.\n')
print('The correct answer: ' + Answer_q26 + '.\n')

if(Response_q26 == Answer_q26):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-seventh question, you put ' + Response_q27 + ' as your answer.\n')
print('The correct answer: ' + Answer_q27 + '.\n')

if(Response_q27 == Answer_q27):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-eighth question, you put ' + Response_q28 + ' as your answer.\n')
print('The correct answer: ' + Answer_q28 + '.\n')

if(Response_q28 == Answer_q28):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the twenty-ninth question, you put ' + Response_q29 + ' as your answer.\n')
print('The correct answer: ' + Answer_q29 + '.\n')

if(Response_q29 == Answer_q29):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('For the thirtieth question, you put ' + Response_q30 + ' as your answer.\n')
print('The correct answer: ' + Answer_q30 + '.\n')

if(Response_q30 == Answer_q30):
	print('Okayyyyyy. Heard you. *Loud applause*')
else:
	print('Yikes. Better luck next time, I guess.')

Continue = input('\nPress the Enter key to continue.')

print('\n====================================================================\n')

print('Thank you so much for playing. Enjoy the rest of your day. :)')
