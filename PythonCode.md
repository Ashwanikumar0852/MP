class student:
    def __init__(self,names,ages,courses,rollnos,dobs):
        self.name=names
        self.age=ages
        self.course=courses
        self.rollno=rollnos
        self.dob=dobs

s1=student("Rahul",23,"Btech",12,"02-03-1994")        
s2=student("Manoj",28,"Btech",16,"09-07-1996") 
s3=student("Amit",26,"Btech",19,"16-09-1997") 

print(str(s1.rollno)+" : "+s1.name)
print(str(s2.rollno)+" : "+s2.name)
print(str(s3.rollno)+" : "+s3.name)