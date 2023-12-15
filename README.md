# project-1
#related to  code a game for hand cricket

print('\t\tHAND CRICKET\t\t')
print('\t\t5 OVER MATCH\t\t')
l=['ODD','EVEN']
print('1.',l[0],'\n2.',l[1])
m = input("CHOOSE : ")
if m in ('odd','ODD'):
 n = int(input('ENTER A NUMBER FOR TOSS : '))
 import random
 k = random.randrange(11)
 d = n+k
 if d%2!= 0 :
  print('you won the toss opt to : ')
  l2=['BAT','BOWL']
  print('1.',l2[0],'\n2.',l2[1])
  r=input("DECISION : ")
  if r in ('bat','BAT'):
      print("\t\tCOMPUTER READY TO BOWL\n\t\t1st INNINGS")
      sum=0
      for i in range(1,31):
       import random
       n = random.randrange(11)   
       k=int(input('BAT :'))
       print(n)
       if k == n :
        print(' BATSMEN OUT')
        print('runs scored',sum,'\nruns needed to win for the computer',sum+1)
        break
       elif k==0:
           sum=sum+n
           continue
       else:
           sum=sum+k
           continue
       print('\n\t\t2nd INNINGS') 
      sum1=0
      for i in range(1,31):
       import random
       n = random.randrange(11)   
       k=int(input('BOWL :'))
       print(n)
       if k == n :
        print(' BATSMEN OUT')
        if sum1 < sum:
            print('YOU WON\nruns scored by the computer',sum1)
        break
       elif n==0:
           sum1=sum1+k
           continue
       else:
           sum1=sum1+n
           if sum1 > sum:
               print('COMPUTER WON',sum1,'runs scored by computer')
           
  else:
       print("\t\tCOMPUTER READY TO BAT\n\t\t1st INNINGS")
       sum=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('BOWL :'))
        print(n)
        if k == n :
         print(' COMPUTER OUT')
         print('runs scored',sum,'\nruns needed to win the game',sum+1)
         break
        elif n==0:
            sum=sum+k
            continue
        else:
           sum=sum+n
           continue
        print('\n\t\t2nd INNINGS') 
       sum1=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('Bat :'))
        print(n)
        if k == n :
         print(' BATSMEN OUT')
         if sum1 < sum:
             print('COMPUTER WON\nruns scored by you',sum1)
         break
        elif k==0:
            sum1=sum1+n
            continue
        else:
            sum1=sum1+k
            if sum1 > sum:
               print('YOU WON',sum,'runs scored by computer')
            
      
 else  :
  print('you lost the toss ')
  l2=['BAT','BOWL']
  c=(random.choice(l2))
  print('COMPUTER CHOOSE TO',c)
  if c in ('bat','BAT'):
       print("\t\tCOMPUTER READY TO BAT\n\t\t1st INNINGS")
       sum=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('BOWL :'))
        print(n)
        if k == n :
         print(' COMPUTER OUT')
         print('runs scored',sum,'\nruns needed to win the game',sum+1)
         break
        elif n==0:
            sum=sum+k
            continue
        else:
           sum=sum+n
           continue
        print('\n\t\t2nd INNINGS') 
       sum1=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('Bat :'))
        print(n)
        if k == n :
         print(' BATSMEN OUT')
         if sum1 < sum:
             print('COMPUTER WON\nruns scored by the you',sum1)
         break
        elif k==0:
            sum1=sum1+n
            continue
        else:
            sum1=sum1+k
            if sum1 > sum:
               print('YOU WON',sum,'runs scored by computer')
            
  else:
   print("\t\tCOMPUTER READY TO BOWL\n\t\t1st INNINGS")
   sum=0
   for i in range(1,31):
    import random
    n = random.randrange(11)
    k=int(input('BAT :'))
    print(n)
    if k == n :
     print(' BATSMEN OUT')
     print('runs scored',sum,'\nruns needed to win for the computer',sum+1)
     break
    elif k==0:
        sum=sum+n
        continue
    else:
     sum=sum+k
     continue
    print('\n\t\t2nd INNINGS') 
    sum1=0
    for i in range(1,31):
     import random
     n = random.randrange(11)   
     k=int(input('BOWL :'))
     print(n)
     if k == n :
      print(' BATSMEN OUT')
      if sum1 < sum:
       print('YOU WON\nruns scored by the computer',sum1)
       break
     elif n==0:
         sum1=sum1+k
         continue
     else:
        sum1=sum1+n
        if sum1 > sum:
         print('COMPUTER WON',sum1,'runs scored by computer')
         
      
if m in ('even','EVEN'):
 n = int(input('ENTER A NUMBER FOR TOSS : '))
 import random
 k = random.randrange(11)
 d = n+k
 if d%2 == 0 :
  print('you won the toss opt to : ')
  l2=['BAT','BOWL']
  print('1.',l2[0],'\n2.',l2[1])
  r=input("DECISION : ")
  if r in ('bat','BAT'):
      print("\t\tCOMPUTER READY TO BOWL\n\t\t1st INNINGS")
      sum=0
      for i in range(1,31):
       import random
       n = random.randrange(11)   
       k=int(input('BAT :'))
       print(n)
       if k == n :
        print(' BATSMEN OUT')
        print('runs scored',sum,'\nruns needed to win for the computer',sum+1)
        break
       elif k==0:
           sum=sum+n
           continue
       else:
           sum=sum+k
           continue
       print('\n\t\t2nd INNINGS') 
      sum1=0
      for i in range(1,31):
       import random
       n = random.randrange(11)   
       k=int(input('BOWL :'))
       print(n)
       if k == n :
        print(' BATSMEN OUT')
        if sum1 < sum:
            print('YOU WON\nruns scored by the computer',sum1)
        break
       elif n==0:
           sum1=sum1+k
           continue
       else:
           sum1=sum1+n
           if sum1 > sum:
               print('COMPUTER WON',sum1,'runs scored by computer')
           
  else:
       print("\t\tCOMPUTER READY TO BAT\n\t\t1st INNINGS")
       sum=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('BOWL :'))
        print(n)
        if k == n :
         print(' COMPUTER OUT')
         print('runs scored',sum,'\nruns needed to win the game',sum+1)
         break
        elif n==0:
            sum=sum+k
            continue
        else:
           sum=sum+n
           continue
        print('\n\t\t2nd INNINGS') 
       sum1=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('Bat :'))
        print(n)
        if k == n :
         print(' BATSMEN OUT')
         if sum1 < sum:
             print('COMPUTER WON\nruns scored by the you',sum1)
         break
        elif k==0:
            sum1=sum1+m
            continue
        else:
            sum1=sum1+k
            if sum1 > sum:
               print('YOU WON',sum,'runs scored by computer')
   
 else  :
  print('you lost the toss ')
  l2=['BAT','BOWL']
  c=(random.choice(l2))
  print('COMPUTER CHOOSE TO',c)
  if c in ('bat','BAT'):
       print("\t\tCOMPUTER READY TO BAT\n\t\t1st INNINGS")
       sum=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('BOWL :'))
        print(n)
        if k == n :
         print(' COMPUTER OUT')
         print('runs scored',sum,'\nruns needed to win the game',sum+1)
         break
        elif n==0:
            sum=sum+k
            continue
        else:
           sum=sum+n
           continue
        print('\n\t\t2nd INNINGS') 
       sum1=0
       for i in range(1,31):
        import random
        n = random.randrange(11)   
        k=int(input('Bat :'))
        print(n)
        if k == n :
         print(' BATSMEN OUT')
         if sum1 < sum:
             print('COMPUTER WON\nruns scored by the you',sum1)
         break
        elif k==0:
            sum1=sum1+n
            continue
        else:
            sum1=sum1+k
            if sum1 > sum:
               print('YOU  WON',sum,'runs scored by computer')
            
  else:
   print("\t\tCOMPUTER READY TO BOWL\n\t\t1st INNINGS")
   sum=0
   for i in range(1,31):
    import random
    n = random.randrange(11)
    k=int(input('BAT :'))
    print(n)
    if k == n :
     print(' BATSMEN OUT')
     print('runs scored',sum,'\nruns needed to win for the computer',sum+1)
     break
    elif k==0:
        sum=sum+n
        continue
    else:
     sum=sum+k
     continue
    print('\n\t\t2nd INNINGS') 
    sum1=0
    for i in range(1,31):
     import random
     n = random.randrange(11)   
     k=int(input('BOWL :'))
     print(n)
     if k == n :
      print(' BATSMEN OUT')
      if sum1 < sum:
       print('YOU WON\nruns scored by the computer',sum1)
       break
     elif n==0:
         sum1=sum1+k
         continue
     else:
        sum1=sum1+n
        if sum1 > sum:
         print('COMPUTER WON',sum1,'runs scored by computer')
         
  


