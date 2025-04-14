class Person:
    def __init__(self, name, age, department, year):
        self.name = name
        self.age = age
        self.department = department
        self.year = year

    def introduce(self):
        print("Hey there! 😊")
        print(f"My name is {self.name}, I'm {self.age} years old.")
        print(f"I'm currently a {self.year} year student in {self.department}.")
        print("I'm passionate about learning, coding, and improving myself every single day.")
        print("I'm just getting started on my journey as a developer, and I'm super excited about what the future holds!")
        print("Nice to meet you, and thanks for stopping by! 🚀")

# Create an instance of Person for Hüseyincan
huseyincan = Person(
    name="Hüseyincan Ergün",
    age=23,
    department="Computer Programming",
    year="1st"
)

# Call the introduction method
huseyincan.introduce()
