# Anki
Some code for creating Anki flashcards. Or testing yourself

Make shure Anki is installed and currently running on your machine.
You also need to install the extension [anki connect](https://github.com/FooSoft/anki-connect)

The "test your understanding.txt" questions are from the Machine Learning 2023 course by Prof. Dr. Rainer Gemulla and Tutor Tommaso Green at the University of Mannheim.

You can create your own "test your understanding answers \<your name\>.txt" files which will be included in the anki cards. It is also possible to draw questions and answer them directely using an input bar window. Those answers will be included in the anki cards and an answer file will be created (optional). 
If you put answers in a answer file, use the format "\<tut number\> \<question id (e.g. 'j' or '10')\>) \<answer\>"
If you have creates an answer file, feel free to share it here.


Additionaly to creating Anki cards, you can also use the code directly to test yourself using the test() function.
You can choose:
- the number of questions
- wether answered or unanswered questions should be shown
- if answers should be shown (if there are any)
- which chapters to choose qustions from 
- if the answers should be stored in the answer_dict from which the anki cards are created and or if they should be saved in a txt file 

