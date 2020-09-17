# Prime-Game
'''
AUTHOR=SAURABH JAIN(AMITY UNIVERSITY)
'''
n=int(input())
m=int(input())
s=[]
for i in range(n,m+1):
    if i==1:
        continue
  

  
    # flag variable to tell
    # if i is prime or not 
    flag = 1
      
    for j in range(2, i // 2 + 1): 
        if (i % j == 0): 
            flag = 0
            break
          
    # flag = 1 means i is prime 
    # and flag = 0 means i is not prime 
    if (flag == 1): 
        s.append(i)
#print(s)
k=n*m
l=n//2*m//2
#print(k,l)
for i in range(len(s)):
    for j in range(i+1,len(s)):
        #print(s[i]*s[j])
        if l<(s[i]*s[j]) and (s[i]*s[j])<k:
            print(s[i],s[j],sep=",")
        else:
            break




