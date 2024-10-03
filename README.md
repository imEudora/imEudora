class Developer:
    def __init__(self):
        self.name = "Eudora"
        self.role = "Software Engineer"
        self.language_spoken = ["Mandarin", "Taiwanese", "English"]
        self.code = ["Python", "JavaScript"]
        self.tools = ["Django", "htmx", "Alpine.js", "Tailwind CSS", "Docker", "PostgreSQL"]
        self.challenge = "Focused on a journey in software engineering, enjoying the daily process of gaining knowledge."

    def say_hi(self):
        print("Let’s dive into the code！")

me = Developer()
me.say_hi()
