# project-1
#Student Grading Program
marks=int(input("enter your marks: "))
if marks>=90:
    print("A+")
elif marks>=80 and marks<=89:
    print("A")
elif marks>=70 and marks<=79:
    print("B")
elif marks>=60 and marks<=69:
    print("C")
elif marks>=50 and marks<=59:
    print("D")
elif marks<50:
    print("Fail")
else:
    print("invalid marks")
