# Markdown for Netbeans ![Description Here](https://raw.githubusercontent.com/moacirrf/netbeans-markdown/main/images/nblogo48x48.png)

***




                  Tutorial 1
Questiont 1:
 IPO Model:
1.input:two numbers
2.Process:Multiplication operation
3.Output:Product result
Pseudocode:
Start:
Input num1
Input num2
Result = num1*num2
Output result
End

Flowchart:
Start→Input num1→Input num2→result=num1*num2→Output result→End
 
Question 2:
IPO model:
1.Input:Random number
2.Process:Comparison judgment
3.Output:Judgment result

Pseudocode:
Start
Random_num=Generate random number(0-100)
If random_num>50 then
Output “Greater than 50”
Else
Output”less than or equal to 50”
End 

Flowchart:
Start→Generate random number→Judgment>50?→Yes→Output”Greater than 50”→End
                                               ↓No→Output”less than or equal to 50”→End

Question3:
IPO Model:
1.Input:Score
2.Process:Compare with 40
3.Output:Pass/fail

Pseudocode:
Start
Input mark
If mark>=40 Then
Output “pass”
Else
Output”fail”
End

Flowchart:
Start→Input mark→Judgment>=40?→Yes→Outprint”pass”→End
                                   ↓No→Output”fail”→End

Question4;
1.Input:Two dice points
2.Process:Compare sizes
3.Output:Game result

Pseudocode:
Start
Dice1=Genarate random number(1-6)
Dice2=Generate random number(1-6)
Output”Player1 points:”,dice1
Output”Player2 points:”,dice2
If dice1>dice2 then Output “Player1 wins”
Else if dice2>dice1 Then Output “Player2 wins”
End

Question5：
IPO Model:
1.Input:length and width
2.Process:Perimeter calculation
3.Output:Perimeter value
Pseudocode:
Start
Input length
Input width
Perimeter = 2 *(length+width)
Output perimeter
End

Question6:
1.Input:10 random numbers
2.Process:Compare to find minimum value
3.Output:Minimum value

Pseudocode:
Start
Min =100
For i from 1 to 10
Num= Generate random number(1-100) 
Output random number,i,”:”,num
If num <min then 
Min=num

End

Flowchart:
Start→min=100→i=1→Generate random number→OUtput random number→Judgment num<min→Yes→min=num

Question7
IPO Model:

· Input: None (10 random numbers 10-100 generated)
· Process: Count odd and even numbers
· Output: Odd count and even count

Pseudocode:

```
start
  SET even_count = 0, odd_count = 0
  FOR i = 1 TO 10
    num = RANDOM(10,100)
    PRINT "Random " + i + ": " + num
    IF num MOD 2 == 0 THEN
      even_count = even_count + 1
    ELSE
      odd_count = odd_count + 1
    END IF
  NEXT i
  PRINT "Even numbers: " + even_count
  PRINT "Odd numbers: " + odd_count
end```

Flowchart:

· Start → Initialize even_count=0, odd_count=0 → Loop i=1 to 10: Generate num → Print num → Decision: num MOD 2 = 0? → Yes: even_count++ → No: odd_count++ → Loop end → Print even_count, odd_count → End

---

Part II

Question8
IPO Model:

· Input: Sentence
· Process: Count 'U' and 'M' characters (case insensitive)
· Output: Count of U and M

Pseudocode:

```
start
  INPUT sentence
  SET count_U = 0, count_M = 0
  
  FOR EACH character IN sentence
    IF character == 'U' OR character == 'u' THEN
      count_U = count_U + 1
    END IF
    IF character == 'M' OR character == 'm' THEN
      count_M = count_M + 1
    END IF
  NEXT character
  
  PRINT "U count: " + count_U
  PRINT "M count: " + count_M
end
```

Flowchart:

· Start → Input sentence → Initialize count_U=0, count_M=0 → Loop each character: Check for 'U/u' → Yes: count_U++ → Check for 'M/m' → Yes: count_M++ → Loop end → Print counts → End

---

Question9:
IPO Model:

· Input: Web page text, keyword
· Process: Count keyword occurrences
· Output: Frequency count

Pseudocode:

```
start
  INPUT web_text
  INPUT keyword
  SET count = 0
  SPLIT web_text INTO words
  
  FOR EACH word IN words
    IF word == keyword THEN
      count = count + 1
    END IF
  NEXT word
  
  PRINT "Keyword frequency: " + count
end
```

Flowchart:

· Start → Input web_text → Input keyword → Initialize count=0 → Split text → Loop each word: Decision: word = keyword? → Yes: count++ → Loop end → Print count → End

---

Question10
IPO Model:

· Input: None (100 random genders generated)
· Process: Count female students
· Output: Female count

Pseudocode:

```
Start
  SET female_count = 0
  FOR i = 1 TO 100
    gender = RANDOM('Male','Female')
    IF gender == 'Female' THEN
      female_count = female_count + 1
    END IF
  NEXT i
  PRINT "Female students: " + female_count
end
```

Flowchart :

· Start → Initialize female_count=0 → Loop i=1 to 100: Generate gender → Decision: gender = 'Female'? → Yes: female_count++ → Loop end → Print female_count → End

---

Question11
IPO Model:

· Input: None (5 random numbers generated)
· Process: Generate numbers and sort descending
· Output: Sorted list

Pseudocode:

```
start
  CREATE array numbers[5]
  FOR i = 0 TO 4
    numbers[i] = RANDOM
  NEXT i
  
  SORT numbers DESCENDING
  PRINT "Sorted numbers: " + numbers
end
```

Flowchart:

· Start → Initialize array → Loop i=0 to 4: Generate number → Store in array → Loop end → Sort array descending → Print array → End

---

Question12
IPO Model:

· Input: User guesses
· Process: Compare guesses with target number
· Output: Feedback messages

Pseudocode:

```
START
  target = RANDOM(1,100)
  SET guess = 0
  
  WHILE guess != target
    INPUT guess
    IF guess < target THEN
      PRINT "Too low"
    ELSE IF guess > target THEN
      PRINT "Too high"
    ELSE
      PRINT "Correct!"
    END IF
  END WHILE
END
```

Flowchart：

· Start → Generate target → Initialize guess=0 → Loop while guess ≠ target: Input guess → Decision: guess < target? → Yes: Print "Too low" → No: Decision: guess > target? → Yes: Print "Too high" → No: Print "Correct" → Loop end → End
