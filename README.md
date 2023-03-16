# Class-Object-Programe
class trainer:
    def _init_(self,name,bio,experience):
        self.name=name
        self.bio=bio
        self.experience=experience
    def display(self):
        print("name: " + self.name)
        print("bio: " + self.bio)
        print("experience: " + self.experience)
trainer1=trainer("Kevin_Brown","Yoga_Instructor","10_Years_experience_in_Yoga_Class")
trainer1.display()
trainer2=trainer("Chris_Patterson","Personal Trainer","15 Years of experience in personal training")
trainer2.display()
trainer3=trainer("Reba Smith","Sports trainer","Worked with athletes in a variety of sports")
trainer3.display()

class facility:
    def _init_(self,name,location):
        self.name=name
        self.location=location
    def display(self):
        print("Name: "+ self.name)
        print("Location: "+ self.location)
facility1=facility("Personal Trainer","Willington CBD")
facility1.display()

class equipment:
    def _init_(self,name,type):
        self.name=name
        self.type=type
    def display(self):
        print("Name : "+self.name)
        print("Type : "+self.type)
equip1=equipment("Bench Press","Weight Trainer")
equip2=equipment("Pilates Equipment","Yoga")
equip3=equipment("Endless Pool","Swimming")
equip1.display()
equip2.display()
equip3.display()
