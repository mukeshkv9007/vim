# vim ( improvised Vi)
 Documentation of vim basic operation

#### basics

| How to  ?  | command |
| ------------- | ------------- |
| Open Vim Editor | vim  |
| Close editor | :q |
| Close editor without saving| :q! |
| Save and Close editor| :wq |
| Default Mode is Command Mode | commands without : |
| Open Insert Mode   | i  |
| Exit Insert Mode   | esc  |
| Command line mode   | commands starts with :  |
| Read-only mode | vim -R message.txt  |
| Edit Existing file  | vim filename.txt  |
| Help |  :help |

#### Editing
| How to  ?  | command |
| ------------- | ------------- |
| Insert text before cursor  |  i |
| Insert text at the beginning of line  |  I |
| Append text after cursor | a |
| Append text at the end of line | A |
| Open new line below cursor | o |
| Open new line above cursor | O |
| substitute single character | s |
| To substitute entire line  | S |
| change text from current cursor position |  C |
| change text from current cursor position | |
| to change text in current line | CC|
| replace single character | r |
| replace entire line  | R |
| join two lines | J |

#### Editing 2  

#### Navigation
| How to  ?  | command |
| Move cursor to left  | h |
| Move cursor to right  | l |
| Move cursor to upward  | k |
| Move cursor to downward  | j |
| to navigate cursor 10 line below | 10j |
| Move cursor to the beginning of current line | 0 |
| Move cursor to the end of current line | $ |
| Scroll down entire page | ctrl+f |
| Scroll up entire page | Ctrl + b |
| Jump to the nth line | :n |
| Jump to the start of file | :0 |
| Jump to the end of file | :$ |
| Move cursor to the beginning of the next word | w |
| Move cursor to the end of the current word | e |
| Move cursor to the beginning of the previous word | b |
| jump list keeps tracks of all the places | :jumps |
| Jump back to the previous position | ctrl+o |
| Jump to the next position | ctrl+i |


#### Searching 

#### Multiple files
#### Multiple buffers
#### Multiple windows
#### Multiple tabs

#### Fold only show selected potion of file

#### Vim - Registers
#### Macro
#### Marker 



#### Difference
| Show differences between files | vimdiff <file> <file> |



#### MISC
| How to  ?  | command |
| highlight miss-spelled words |  :set spell |
| complete word | ctrl+p |
| Indent | =% |
| Access Remote File | vim scp://user@server.com/filepath |
| Net Read | :Nread scp://jarvis@localhost//tmp/message.txt |
| Net Write | :Nwrite scp://jarvis@localhost//tmp/message.txt | 
| syntax highlighting | :syntax on / :syntax off |
| set indentation | : set autoindent : set smartindent |
| Show differences between files | vimdiff <file> <file> |

#### Execute shell commands
| Execute singlt shell command | :!<command>|
| | :shell |