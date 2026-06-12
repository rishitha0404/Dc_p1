while True:
    user = input("You: ").lower()

    if user in ["hi", "hello", "hey"]:
        print("Bot: Hello! How can I help you?")
    elif user == "how are you":
        print("Bot: I'm fine. Thanks for asking!")
    elif user in ["bye", "exit", "quit"]:
        print("Bot: Goodbye!")
        break
    else:
        print("Bot: Sorry, I don't understand that.")
