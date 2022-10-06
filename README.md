
# Hi, I'm Ramya Lakhani! 👋


# Project Title

I am a student who is learning Python and as my first mini project I can consider this game 

This is a simple word game which is created using python only

In this game you just need to create python file and paster the code there 

after this you can just run the code and it will ask you a simple question that 

1) You want to play the game or not enter (yes or no)

2) It will ask just 4 question to you like 
    
    --> Who is the creator of the github and CEO of Microsoft and best os and python's framework




## Authors

- [@rlakhani](https://github.com/rlakhani21)
## Acknowledgements



## Usage/Examples

To use this game follow the steps which are given below 

step 1 : Install python in your windows/mac/linux machine 

step 2: After installing python go to your command prompt/terminal and paste the following link

```python
pip install colorama
```

step 3 : After installing the colorama module enter the following command to your command line/terminal 

```python
pip install tk
```
OR 

You can simply run the into the vs code or more advanced IDEs

to easily copy here the code is:

```python
"""    
This is a basic word game for the python first project 

"""
import tkinter
from tkinter import *
from tkinter import messagebox as tkmb
import colorama
from colorama import Fore,Back,Style
colorama.init(autoreset = True)
# game code start 

ans = input(Fore.RED+'Your want to start the game(yes / no ) : ')
score = 0
ques= 4

if ans.lower() == "yes":
    print(Back.CYAN+'What is the name of creator of github ? : ')
    que1 = input(Fore.CYAN + Back.LIGHTMAGENTA_EX+Fore.RESET)
    que1 = que1.replace(" ", "")
  
    if que1.lower() == "linustorvald":
        print(Fore.GREEN+"Correct Answer")
        score += 1
    else:
        print(Fore.RED+"Incorrect Answer")
    
    print(Back.CYAN+"What is the CEO of Microsoft ? : ")
    que2 = input(Fore.CYAN + Back.LIGHTMAGENTA_EX + Fore.RESET)
    que2 = que2.replace(" ", "")
    if que2.lower() == "sathyanadella" or que2.lower() == "sathya":
        print(Fore.GREEN+"correct")
        score += 1
    else:
        print(Fore.RED+"inocorrect")
    
    print(Back.CYAN+'What is the name of the best operating system ? : ')
    ques3 = input(Fore.CYAN + Back.LIGHTMAGENTA_EX + Fore.RESET)
    ques3 = ques3.replace(" ", "")
    ques3=ques3.lower()
    if ques3.endswith('linux'):
        print(Fore.GREEN+"correct")
        score += 1 
    else:
        print(Fore.RED+ "incorrect")
        
    print(Back.CYAN+'Enter one of the python framework name ? :')
    ques4 = input(Fore.CYAN + Back.LIGHTMAGENTA_EX + Fore.RESET )
    ques4 = ques4.replace(" ", "")
    if ques4.lower() == "django" or ques4.lower() == "flask" :
        print(Fore.GREEN+'correct')
        score+=1
    else: 
        print(Fore.RED+'incorrect')
        
        
    total_score = (score/ques)*100
    print(Back.LIGHTBLUE_EX+ Fore.GREEN+"SCORE IS : "+str(total_score) + "%") 
print('Good Bye')
tkmb.showinfo('passed','scoreis '+ str(total_score)+ "%")
  
  

```


## Support

For support, email rlakhani759@rku.ac.in or go to my linked in and message me 


## 🚀 About Me
I'm a Python adn Django Developer 

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramyakumar-lakhani-8b20ba248/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/rlakhani759)

