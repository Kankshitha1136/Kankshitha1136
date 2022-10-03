- 👋 Hi, I’m @Kankshitha1136
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Kankshitha1136/Kankshitha1136 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
a=[]
n= int(input("Enter the number of elements in list:"))
for x in range(0,n):
    element=input("Enter element" + str(x+1) + ":")
    a.append(element)
min1=len(a[0])
temp=a[0]
for i in a:
    if(len(i)<min1):
       min1=len(i)
       temp=i
print("The word with the shortest length is:")
print(temp)
