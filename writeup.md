# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
I think I got much better at learning how to work with lists and tuples in python and general problem solving during this assignment. I also learned how to code a simple pattern matching function that uses user input and get an answer from that.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
The user types in a query, then the match function tries to find a pattern from it from the predefined source lists. If it finds a match it extracts the words that are in _ or %. Match is called inside the method search_pa_list, it returns the extracted words, if matches is not None, it calls the corresponding action function from pa_list. When the action function is called, it returns the value to the user.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
Some real world applications of this could be customer support bots for many companies because most people are often asking the same questions so they find patterns in the questions and return the answer.
To improve this system you would have to have some way to have more patterns to handle like spelling mistakes or different wordings because not everyone words their questions the same way.