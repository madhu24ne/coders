import random

greetings = ['hai', 'hello', 'hi', 'Hi', 'hey!','hey']
random_greeting = random.choice(greetings)

question = ['How are you?','How are you doing?']
responses = ['Okay',"I'm fine"]
random_response = random.choice(responses)

need=['i need help','can you help me to know about']
answers=['of course']
random_need=random.choice(answers)


while True:
	userInput = raw_input(">>> ")
	if userInput in greetings:
		print(random_greeting)
	elif userInput in question:
		print(random_response)
        elif userInput in need:

	        print(random_need)
                print("press c to know about c language and p to know about python")
                answer= input('what do you want to know?') 
                if(answer=='c'):
                   print("you visit www.freshtofresh.com") 
                elif(answer=='p'):
                    print("please visit www.thinkpython.com")
                     
	else:
		print("I did not understand what you said")

