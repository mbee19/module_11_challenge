# module_11_challenge
Module 11 Challenge for Morgan Bee

In this challenge, I used all class activities from Module 11 and from Module 5. I also used Khaled's class notes in the juptyer notebook to help me through the challenge. 

Chat GPT helped me with this line of code: name = [header.get_text(strip = True) for header in headers] in the part 2 notebook to loop through the scraped data to find the correct information needed for the dataframe, for both the headers and the data. 

I used this Stack Overflow article (https://stackoverflow.com/questions/67848494/python-pandas-to-datetime-attributeerror-tuple-object-has-no-attribute-lower) to help me with this line of code: 
    mars_df.columns = ['id', 'terrestrial_date', 'sol', 'ls', 'month', 'min_temp', 'pressure'] 
in order to name the headers so that I could successfully convert the column to a datetime type. 

I used this Stack Overflow article (https://stackoverflow.com/questions/72396287/sort-pandas-series-both-on-values-and-index) to help me with this line of code: 
    sorted_temp = avg_min_temp.sort_values(axis = 0, ascending = True)
in order to sort the temperature and the pressure in Part 2 of this challenge. 