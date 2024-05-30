# WORD QUIZ

## Description
WordQuiz is a program for learning English words by C language.
It can show the list of the voca1, voca2 and add or edit the list, test words inbound the voca

## How to install and run the project
You can bring my wordquiz files
- git clone https://github.com/hcy0157/Personal_wordquiz.git

And you shoud make .exe file
- gcc -o <name>.exe wordquiz.c show_words.c run_test.c read_line.c menu.c list_wordbooks.c file_test.c

Finally you can execute the exe file
./<name>.exe

## How to use the porject
It can show 4 lists 

1. List all wordbooks
It shows the voca in the wordbooks directory. At first, It may show "voca1", "voca2".

2. Show the words in a wordbook
It shows the voca list and you can choose the voca. If you choose the voca, the words in that the voca will be printed out.
And you'll see three options: add words, edit words and exit.

Add words: you can input word and meaning that you want. Then the word will be saved in the voca

Edit words: if a certain word in the voca has a typo or has a wrong meaning, try this option. If you enter the corresponding word, you can enter a new word and meaning.

Exit: you can go back to the main menu.

3. Test with a wordbook
You can test the words. you can choose the voca in a wordbook. Then the program asks the meaning of the word, you can answer the word. At the end, you can see how many questions you got right.

4. Exit
You can turn out the program with 4. 

## Credits
Our team(English for software 208) makes and modify this project. 
Member: yheecb, pringleshu, hcy0157 

## License