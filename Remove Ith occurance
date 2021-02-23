#4 Program to remove the “i” th occurrence of the given word in a list
str1=input("Enter a sentence:").split(" ")
print("Original List:",str1)
st=list(set(str1))
for i in st:
 print("{}:{}".format(i,str1.count(i)))
word=input("Enter word to remove:")
i=int(input("Enter 'i'th occurence no."))
j=0 #to compare occurances
k=-1 #points to each element in list
for w in str1:
 k=k+1
 if(w==word):
 if((j+1)==i):
 str1.pop(k)
 break
 else:
 j=j+1
print("Updated List:",str1)
