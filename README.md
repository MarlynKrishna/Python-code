# Python-code

def Count_Total_Words(str1):
total = 1
for i in range(len(str1)):
if(str1[i] == ' ' or str1 == '\n' or str1 == '\t'):
total = total + 1
return total
  

#Converts the string into lowercase
string = string.lower();

#Split the string into words using built-in function
words = string.split(" ");

print("Duplicate words in a given string : ");
for i in range(0, len(words)):
 count = 1;
 for j in range(i+1, len(words)):
     if(words[i] == (words[j])):
         count = count + 1;
 #Set words[j] to 0 to avoid printing visited word
 words[j] = "0";

 #Displays the duplicate word if count is greater than 1
 if(count > 1 and words[i] != "0"):
     print(words[i],": ",count[i]);
     string = input("Please Enter your Own String : ")
     leng = Count_Total_Words(string)
     print("Total Number of Words in this String = ", leng)



