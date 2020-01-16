# Terminal_Quiz
Commandline based flashcard program for Linux. Default question-bank with basic Linux terminal commands and excerices

### INSTRUCTIONS
move the manpage `mv qme.1 /usr/local/man/man1/`\
add the foll to the end of ~/.bashrc: `rm ~/bin/qme_session.log` \
create the alias: `alias qme="~/Documents/Terminal_Quiz/qme"` 

### NAME 
qme - flashcard management program
  
 ### OPTIONS 

  >-c \
      shows the number times qme was called in this terminal session.
  
  >-t \
      shows the total number of times qme was called.

 > -q, --question &lt;question number&gt; \
      shows the Nth question
      
  >-a, --answer &lt;question number&gt;\
      shows the answer to the Nth question.

  >-e &lt;"question num"&gt;  &lt;"new question" &gt;\
      edit or replace indicated question

  >-f &lt;"answer num"&gt;  &lt;"new answer" &gt;\
      edit or replace indicated answer
  
  >--add &lt;"question"&gt;  &lt;"answer" &gt;\
      adds a question and answer to the bank
  
  >--remove &lt;question number&gt;\
      permanantly removes indicated question.

  >--clear-log \
      Clear alltime log. This sets total count of random questions seen to zero.

  >--reset \
      Reset the question and answer database to default.
  

      
      
