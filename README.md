# Terminal_Quiz
Commandline based flashcard program for Linux. Default question-bank with basic Linux terminal commands and excerices

### INSTRUCTIONS
create the alias: `alias qme="~/Documents/Terminal_Quiz/qme"` \
adding the foll to the end of ~/.bashrc: `rm ~/bin/qme_session.log` 
move the manpage `mv qme.1 /usr/local/man/man1/` 

### NAME 
qme - displays a random question
  
 ### OPTIONS 

  >-c \
      shows the number times qme was called in this terminal session.
  
  >-t \
      shows the total number of times qme was called.

 > -q, --question &lt;question number&gt; \
      shows the Nth question
      
  >-a, --answer &lt;question number&gt;\
      shows the answer to the Nth question.
  
  >--add &lt;"question"&gt;  &lt;"answer" &gt;\
      adds a question and answer to the bank
  
  >--remove &lt;question number&gt;\
      permanantly removes indicated question.

  >--clear-log \
      Clear alltime log. This sets total count of random questions seen to zero.

  >--reset \
      Reset the question and answer database to default.
  

      
      
