class Student:

    def __init__(self):
        self.name = "David Ackerman"
        self.role = "Student"
        self.age = "15"
        self.language_spoken = "en_US"

    def say_hi(self):
        print("Thanks for visiting my page!")

me = Student()
me.say_hi()
