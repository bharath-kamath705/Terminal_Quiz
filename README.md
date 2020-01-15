# Terminal_Quiz
Commandline based flash card program for Linux. Default question-bank with basic Linux terminal commands and excerices

### INSTRUCTIONS
create the alias: `alias qme="~/Documents/Terminal_Quiz/qme"` \
adding the foll to the end of ~/.bashrc: `rm ~/bin/qme_session.log` 

### NAME 
qme - displays a random question
  
 ### OPTIONS 
 > -q, --question &lt;question number&gt; \
      shows the Nth question
      
  >-a, --answer &lt;question number&gt;\
      shows the answer to the Nth question
  
  >-c \
      shows the number times qme was called in this terminal session
  
  >-t \
      shows the total number of times qme was called
  
  >--remove &lt;question number&gt;\
      permanantly removes indicated question
  
  >--add &lt;"question"&gt;  &lt;"answer" &gt;\
      adds a question and answer to the bank
      
      
