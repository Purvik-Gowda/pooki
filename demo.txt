s=0
import os
import time
def answer():
    for i in range(4):
        ans=input('enter your answer')
        t=ans.lower()
        if i==3 :
            return()

        if (t=='a' or t=='b' or t=='c' or t=='d'):
            return(t)
        else:
            print('invalid option Please  enter the correct option')
            continue

for i in range(0,5):
  import random
  q = random.randint(1,20)
  time.sleep(3)
  os.system ('clear')
  print(i+1)
  match q:
     case 1:
        print ("What is the pH value of the human body?")
        print ("a 9.2 to 9.8")
        print ("b 7.0 to 7.8")
        print ("c 6.1 to 6.3")
        print ("d 5.4 to 5.6")
        ans=answer()
        if ans == "b":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")

     case 2:
        print ("Which of the following are called Key Industrial animals? ")
        print ("a Producers")
        print ("b Tertiary consumers")
        print ("c Primary consumers")
        print ("d None of these")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 3:
        print (" Elections to panchayats in state are regulated by")
        print ("a Gram panchayat")
        print ("b Nagar Nigam")
        print ("c Election Commission of India")
        print ("d State Election Commission")
        ans=answer()
        if ans == "d":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 4:
        print ("Which of the following Himalayan regions is called Shivalik's? ")
        print ("a Upper Himalayas")
        print ("b Lower Himalayas")
        print ("c Outer Himalayas")
        print ("d Inner Himalayas")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 5:
        print ("Forming of Association in India is ")
        print ("a Legal Right")
        print ("b Illegal Right")
        print ("c Natural Right")
        print ("d Fundamental Right")
        ans=answer()
        if ans == "d":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 6:
        print ("The Samkhya School of Philosophy was founded by ")
        print ("a Gautam Buddha")
        print ("b Mahipala")
        print ("c Gopala")
        print ("d Kapila")
        ans=answer()
        if ans == "d":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 7:
        print (" Pustaz grasslands are situated at?")
        print ("a South Africa")
        print ("b China")
        print ("c Hungary")
        print ("d USA")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 8:
        print (" Right to emergency medical aid is a")
        print ("a legal right")
        print ("b Illegal right ")
        print ("c Constitutional right")
        print ("d Fundamental right ")
        ans=answer()
        if ans == "d":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 9:
        print ("Chelaiya Samiti is related to which of the following? ")
        print ("a Banking sector")
        print ("b insurance sector ")
        print ("c Health sector")
        print ("d tax reforms")
        ans=answer()
        if ans == "d":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 10:
        print (" Which of the given devices is used for counting blood cells?")
        print ("a Hmelethometer")
        print ("b Spyscometer")
        print ("c Hemocytometer")
        print ("d Hamosytometer")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 11:
        print ("What is the capital of France?")
        print ("a Berlin")
        print ("b London")
        print ("c Paris")
        print ("d Rome")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 12:
        print ("Who wrote Romeo and Juliet?")
        print ("a William Shakespeare")
        print ("b Charles Dickens")
        print ("c Jane Austen")
        print ("d Mark Twain")
        ans=answer()
        if ans == "a":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 13:
        print ("What is the largest planet in our solar system?")
        print ("a Earth")
        print ("b Jupiter")
        print ("c Saturn")
        print ("d  Mars")
        ans=answer()
        if ans == "b":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 14:
        print ("Which ocean is the largest?")
        print ("a Atlantic Ocean")
        print ("b Indian Ocean")
        print ("c Arctic Ocean")
        print ("d Pacific Ocean ")
        ans=answer()
        if ans == "d":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 15:
        print ("What is the currency of Japan?")
        print ("a Yen")
        print ("b Dollar")
        print ("c Euro")
        print ("d Pound")
        ans=answer()
        if ans == "a":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 16:
        print ("Who is known as the Father of Modern Physics?")
        print ("a Albert Einstein")
        print ("b Isaac Newton")
        print ("c Stephen HawkingMarie Curie")
        print ("d Marie Curie")
        ans=answer()
        if ans == "a":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 17:
        print (" What is the capital of Australia?")
        print ("a Sydney")
        print ("b Melbourne")
        print ("c Canberra")
        print ("d Perth")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 18:
        print ("Who painted the Mona Lisa?")
        print ("a Vincent Van Gogh")
        print ("b Pablo Picasso")
        print ("c Leonardo da Vinci")
        print ("d Michelangelo")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 19:
        print (" Which country is the largest by land area?")
        print ("a  Russia")
        print ("b Canada")
        print ("c China")
        print ("d United States")
        ans=answer()
        if ans == "a":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
     case 20:
        print ("Who painted the famous artwork Guernica?")
        print ("a Vincent van Gogh")
        print ("b Leonardo da Vinci")
        print ("c Pablo Picasso")
        print ("d Michelangelo")
        ans=answer()
        if ans == "c":
          print ("correct answer")
          s+=1
        else:
          print ("wrong answer")
print("you got",s,"out of 20 questions")