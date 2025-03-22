- hello im tev
- im into computers and such
-  I’m currently a student
- he/him 19m



.
    def __init__(self):
        self.tevin_love = True

    def check_love(self):
        while self.tevin_love:
            print("Tevin ❤️ computers! But does the computer love Tevin back? ")
            time.sleep(2)
            if time.time() % 7 == 0:  # Randomly decide the computer's mood
                print("The computer says: 'Yes, Tevin. I love you too. '")
                break

pc = Computer()
pc.check_love()

print(tevin_loves_computers())- 


