# creating a "convert text function"

  

def convert(text) :

    """Replaces emoticons with emojis"""

    text = text.replace(":)", "🙂").replace(":(", "🙁")

    return text

  

# creating the main function

def main() :

    """Prompts user to enter the text with emoticons"""

    user_input = input("Enter the text: ")

    print(convert(user_input))

  

# Calling the main function

  

main()