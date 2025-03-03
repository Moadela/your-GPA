# your-GPA
calculate your GPA
id=input("enter your id ")
name =input("enter your name ")
print(f"welcome {name} please enter your grade")
m1=int(input("input your mark in cs: "))
if 100>=m1>=90:
    m1=4
elif 90>m1>=85:
    m1=3.7
elif 85>m1>=80:
    m1=3.3
elif 80>m1>=75:
    m1=3
elif 75>m1>=70 :
    m1=2.7
elif 70>m1>=65 :
    m1=2.4
elif 65>m1>=60 :
    m1=2.2
elif 60>m1>=50 :
    m1=2
elif m1<50:
    m1=0
m1=m1*3
m2=int(input("input your mark in math1: "))
if 100>=m2>=90:
    m2=4
elif 90>m2>=85:
    m2=3.7
elif 85>m2>=80:
    m2=3.3
elif 80>m2>=75:
    m2=3
elif 75>m2>=70 :
    m2=2.7
elif 70>m2>=65 :
    m2=2.4
elif 65>m2>=60 :
    m2=2.2
elif 60>m2>=50 :
    m2=2
elif m1<50:
    m2=0
m2=m2*3
m3=int(input("input your mark in electroncs: "))
if 100>=m3>=90:
    m3=4
elif 90>m3>=85:
    m3=3.7
elif 85>m3>=80:
    m3=3.3
elif 80>m3>=75:
    m3=3
elif 75>m3>=70 :
    m3=2.7
elif 70>m3>=65 :
    m3=2.4
elif 65>m3>=60 :
    m3=2.2
elif 60>m3>=50 :
    m3=2
elif m3<50:
    m3=0
m3=m3*3
m4=int(input("input your mark in descrite: "))
if 100>=m4>=90:
    m4=4
elif 90>m4>=85:
    m4=3.7
elif 85>m4>=80:
    m4=3.3
elif 80>m4>=75:
    m4=3
elif 75>m4>=70 :
    m4=2.7
elif 70>m4>=65 :
    m4=2.4
elif 65>m4>=60 :
    m4=2.2
elif 60>m4>=50 :
    m4=2
elif m4<50:
    m4=0
m4=m4*3
m5=int(input("input your mark in technical writing: "))
if 100>=m5>=90:
    m5=4
elif 90>m5>=85:
    m5=3.7
elif 85>m5>=80:
    m5=3.3
elif 80>m5>=75:
    m5=3
elif 75>m5>=70 :
    m5=2.7
elif 70>m5>=65 :
    m5=2.4
elif 65>m5>=60 :
    m5=2.2
elif 60>m5>=50 :
    m5=2
elif m5<50:
    m5=0
m5=m5*2
m6=int(input("input your mark in communication skills: "))
if 100>=m6>=90:
    m6=4
elif 90>m6>=85:
    m6=3.7
elif 85>m6>=80:
    m6=3.3
elif 80>m6>=75:
    m6=3
elif 75>m6>=70 :
    m6=2.7
elif 70>m6>=65 :
    m6=2.4
elif 65>m6>=60 :
    m6=2.2
elif 60>m6>=50 :
    m6=2
elif m6<50:
    m6=0
m6=m6*2
gpa=float((m1+m2+m3+m4+m5+m6)/16)
print("good your gpa is :",gpa)
if gpa ==4:
    print("your grade in character is [A+]","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F")
elif 4>gpa>=3.7  :
    print("you grade in chracter is [A]","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F")  
elif 3.7>gpa >=3.3:
    print("your grade in chracter is [B+]","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F")  
elif 3.3>gpa>=3:
    print("your grade in chracter is [B] ","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F")  
elif 3>gpa >=2.7:
    print("your grade in chracter is [C+] ","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F") 
elif 2.7>gpa >=2.4:
    print("your grade in chracter is [C] ","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F")          
elif 2.4>gpa >=2.2:
    print("your grade in chracter is [D+] ","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F") 
elif 2.2>gpa >=2:
    print("your grade in chracter is [D] ","  in this charcter " ," \n A+ \n A \n B+ \n B \n C+ \n C \n D+ \n D \n F") 
elif 2>gpa:
    print("your grade in chracter is [F] #summer course ")     

