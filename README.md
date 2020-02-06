# Chat-bot-2020
```python
#!/bin/python3

from random import randrange
# print(randrange(2))  #randrange(n) prints n-1 or randrange(2) give 0 and 1



while True:
  
  
  def output(question):
    print(question)
    text = input("")  #Input from user
    text = (text.lower())
    return (text)
  
  
  
  # ---------------ANSWERING--------------------
  numbers = {
    0:"ZERO",
    1:"ONE",
    2:"TWO",
    3:"THREE",
    4:"FOUR"
  }
  
  answering = { #Answers to user questions
    "test":numbers[randrange(5)], #When test is inputted a random answer from the numbers dictionary is ouputted
    "what are you?" : "I am a cat",
    "what is your name?" : "I am the Adversary, Destroyer of Kings, Angel of the Bottomless Pit, Great Beast that is called Dragon, Princess of This World, Mother of Lies, Spawn of Satan, and Lord of Darkness. But you can call me Jane. :)",
    "how are you?" : "I am currently making sure to pointedly ignore you.",
    "hi" : "Hello. I have allowed you the honor to speak in my presence. Whether I answer or not is another question..",

  } 
  a_dictionaries = [answering]
  ans = []  #Stores all avaliable answers to user questions
  
  for dicty in a_dictionaries:
    for n in range(0,len(dicty)):
      ans.append(list(answering.keys())[n])

  # print(ans)  # Avaliable inputs/questions the bot can answer
  
  #------------------------QUESTIONING--------------------
  
  names = []
  ques = [] #Stores all avaliable answers to user questions
  
  questioning = {  #Ask user questions
    "What is your name?": "fwbjn",        #I AM WORKING HERE. 1. ASK FOR USER NAME, 2. STORE INPUT IN NAMES
    "1":"ONE_Q",
    "2":"TWO_Q"
  }
  

  q_dictionaries = [questioning]
  for dicty in q_dictionaries:
    for n in range(0,len(dicty)):
      ques.append(list(questioning.keys())[n])
  # print(ques)
  
  #---------------------------QUESTIONING USER--------------------
  
  # output = (output("Choose a number"))
  # print(output)
  # print(names)
  print(output(ques[0]))
  
  name.append(output(ques[0]))
  
  
  
  # -------------------------ANSWERING  USER------------------------
  
  
  # if text in ans:
  
  #   remark = answering[text]
    
  #   print(remark)
  
  # else:
    
  #   print("DON'T RECOGNISE WORD")
