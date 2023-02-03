# Python-code
````
command = ""
car_on = False
car_stopped = False
while command != 'quit' :
    command = input("> ").lower()
    if command == 'help':
        print('''
start-to start the car
stop- to stop the car
quit- to exit
        ''')
    elif command == 'start' and car_on== False:
        print('start- to start the car')
        car_on= True
    elif command == 'start' and car_on== True:
        print('''
        The car is allready on.
        Get out or I'll get the divorce
        ''')
    elif command == 'stop' and car_on ==False:
        print('''
        U should first run the car to stop it!
        U shoud not drive when ur high:(''')
    elif command == 'stop' and car_stopped == True:
        print('''
        The car has allready stopped!
        U shoud not drive when ur high:(''')
    elif command == 'stop' and car_stopped == False:
        print('stop-to stop the car')
        car_stopped= True
    elif command == 'quit' :
        break
    else: print("I don't understand that... please try it again")
````

