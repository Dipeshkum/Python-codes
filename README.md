# Python-codes
How to print the phone is correct or not in a given list.


num=['+91-9892615303','+91-9898989898','+98-1234567899','123456789','12456','+91-0123456789','+121-145452264']
for i in range(len(num)):
    if len(num[i]) == 14 and num[i][0:3] == "+91" or num[i][0:3] == "+98":
        print (f'Number is valid :{num[i]}')
    else:
        print (f'Invalid number:{num[i]}')


Output will be:

Number is valid :+91-9892615303
Number is valid :+91-9898989898
Number is valid :+98-1234567899
Invalid number:123456789
Invalid number:12456
Number is valid :+91-0123456789
Invalid number:+121-145452264

![image](https://user-images.githubusercontent.com/87379035/186409793-b773c608-1171-4153-9275-653870f914c1.png)
