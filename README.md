# Chatbotskillsync
Responses Dictionary:

The responses dictionary contains predefined responses for various user inputs. Each key in the dictionary represents a specific user input or a keyword, and the corresponding value is a list of possible responses for that input.
get_response Function:

The get_response function takes a user input as an argument.
It converts the user input to lowercase to make the comparison case-insensitive.
It iterates through the keys in the responses dictionary to find a match with the user input.
If a match is found, it randomly selects a response from the list of responses associated with that key.
If no match is found, it selects a random response from the "default" key.
Main Chat Loop:

The program starts by printing an initial greeting from the chatbot.
It then enters a while True loop, where it continuously prompts the user for input using input("You: ").
If the user types "exit," the chatbot prints a goodbye message and breaks out of the loop, ending the program.
Otherwise, it calls the get_response function with the user input and prints the generated response.
Example Usage:

The chatbot responds to various user inputs based on the predefined responses in the responses dictionary.
If the user input matches one of the keys, it provides a corresponding response; otherwise, it falls back to a default response.
Random Selection:

The random.choice() function is used to select a random response from the list of possible responses for a given input.
Overall, this code provides a simple demonstration of a chatbot that responds to user inputs with predefined messages. It uses a basic pattern matching approach to determine the appropriate response based on the keywords present in the user input.
