- 👋 Hi, I’m @Kankshitha1136
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

myDict = {'a': 'apple', 'b': 'Banana' , 'o': 'Orange', 'm': 'Mango'}
print("Dictionary : ", myDict)

key = input("Please enter the Key you want to search for: ")


if key in myDict.keys():
    print("\nKey Exists in this Dictionary")
    print("Key = ", key, " and Value = ", myDict[key])
else:
    print("\nKey Does not Exists in this Dictionary")
