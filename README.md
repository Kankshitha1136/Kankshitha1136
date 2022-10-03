- 👋 Hi, I’m @Kankshitha1136
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

# Python program to print downward left half pyramid star pattern 

def pattern(n):
   i = 1
   while i <= n :
      j = n
      while j >= i:
         # printing stars
         print("*", end=" ")
         j = j - 1
      print()
      i = i + 1
 
# take inputs
n = int(input('Enter the number of rows: '))

# calling function
pattern(n)
