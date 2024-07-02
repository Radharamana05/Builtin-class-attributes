# Builtin-class-attributes
# python program that includes dictionary,document,module,bases,name.
class abc():
    def __init__(self,v1,v2):
        self.v1=v1
        self.v2=v2
    def display(self):
        print("variable1=",self.v1)
        print("variable2=",self.v2)
obj=abc(23,14.67)
obj.display()
print("dictionary=",obj.__dict__)
print("document=",obj.__doc__)
print("name=",abc.__name__)
print("bases=",abc.__bases__)
print("module=",obj.__module__)
