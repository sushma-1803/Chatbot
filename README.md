# Chatbot
def simple_chatbot():
    print("Bot: Hi! How can I help you?")
    while True:
        user_input = input("You: ").lower()
        
        if "hello" in user_input:
            print("Bot: Hi there!")
        elif "how are you" in user_input:
            print("Bot: I'm good, thanks!")
        elif "bye" in user_input:
            print("Bot: Goodbye!")
            break
        else:
            print("Bot: I didn't understand that.")

simple_chatbot()
