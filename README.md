<div align="center"><h1>Hi, 👋 I am Franco du Plessis.</h1></div>
<div align="center"><h3>Welcome to my GitHub Repository</h3></div>
<br>

```python
class DeveloperProfile:

    def __init__(self):
        self.full_name = "Franco du Plessis"
        self.profession = "QA Tester, Data Integration & Automation Engineer"
        self.education = "Mechanical Engineer turning Developer"
        self.work_experience = (
            "Over 20 years in engineering, just over 2 years in tech industry"
        )
        self.key_skills = [
            "Python",
            "JavaScript",
            "TypeScript",
            "Selenium",
            "HTML",
            "CSS",
        ]
        self.have_experience = [
            "C#",
            "ASP .NET Core",
            "EF Core",
            "React",
            "Visual Basic Script",
            "C++",
        ]
        self.hobbies = (["Music", "Gaming", "Personal Dev Projects"],)

    def say_hi(self):
        print(
            f"Hi there! I'm {self.full_name}, and I currently work as an {self.profession}."
        )


me = DeveloperProfile()
me.say_hi()
```
