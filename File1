def myfunction(inputList):
    evenPlace=""
    oddPlace=""
    for word in inputList:
        for index,char in enumerate(word):
            if index==0:
                evenPlace=evenPlace+char
            elif index%2==0: #and word.index(letter)!=0:
                evenPlace=evenPlace+char
            elif index%2!=0: #and word.index(letter)!=0:
                oddPlace=oddPlace+char
        print(evenPlace,oddPlace)
        evenPlace=""
        oddPlace=""

N=int(input())
inList=[]
for i in range(N):
    s=input()
    inList.append(s)
myfunction(inList)
