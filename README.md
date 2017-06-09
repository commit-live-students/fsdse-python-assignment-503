# Write a Python program to change the name 'James' to 'Suresh' in name column of the DataFrame.

Define a function that takes in the dictionary 'exam_data' and the list 'labels' given below as parameters. The function should convert the 'exam_data' into a DataFrame with the list 'labels' as the index. The function should change the name "James" to "Suresh" in the name column and return the DataFrame.

    exam_data  = {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
            'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
            'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
            'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}
    labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j'] 