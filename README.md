# assignment-2-1-
#Write a Python program to get a list, sorted in increasing order by the last element in each tuple from a given list of non-empty tuples
#Sample List : [(2, 5), (1, 2), (4, 4), (2, 3), (2, 1)]
#Expected Result : [(2, 1), (1, 2), (2, 3), (4, 4), (2, 5)]


user_input =[(2, 5), (1, 2), (4, 4), (2, 3), (2, 1)]
print ("The user input is: ",user_input)
user_input[0],user_input[4],user_input[2],user_input[3]=user_input[4],user_input[0],user_input[3],user_input[2]
print ("The user output is: ",user_input)
