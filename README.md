# python9
write a python program by using class and objects
class abc():
    class_variable=0
    def __init__(self, var):
        abc.class_variable+=1
        self.var=var
        print("object value:",var)
        print("class value",abc.class_variable)
obj1=abc(10)
obj2=abc(20)
obj3=abc(30)
