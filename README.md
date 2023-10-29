Q1. Explain Class and Object with respect to Object-Oriented Programming. Give a suitable example.
  ans OOPS-CONCEPT OF CLASSES
  OOPS-BLUE PRINT,SCALETEN,MODULAR STRUCTURE
  EXAMPLE-CAR FUNCTION ALL DESCRIPTION LIKE MODEL NAME,COLOUR ALL PROPERTIES MEANS CLASS
  CLASS IS JUST A CLASSIFICATION OF REAL WORLD ENTITY
  EXAMPLE
  a = 1
  print(type(a))
  < class 'int' >
  a =variable of class,instance of class,object of class
  1= class of integer
  object stands for real world entity
  if create class in python
  why we create class in python?
  different types of modules should be structered way thats y  we create class in python 
  in class-we can put variable,function

  module different types in project we make suppose we start to write coding-class is creating module-frontend,backend module
  if we make different types coding-class in that written respective module-
  class  & oop uses -coding capability enhance & code structered,reusable

  class-variable,make mentods,function in structured way we can use class
  ex
      class test:
      
      def welcome_msg():
       print("this is my class")
       
       rohan = test()
       rohan.welcome_msg()
       this is my class
       
       
   Q2. Name the four pillars of OOPs.
   ans.abstraction, encapsulation, inheritance, and polymorphism.is 4 pillars of oops
       
       
       
       
       
   Q3. Explain why the __init__() function is used. Give a suitable example.
   
       __init__- inbuilt function,its called construtor-for using data pass like all details you can put in class
       class pwskills3:
    
    def __init__(self,phone_number,student_id):
        self.phone_number = phone_number
        self.student_id = student_id
        
    def return__rohan = ("shweta", 23456,123)student__details(self):
        return self.phone_number,self.student_id
        
     rohan = ("shweta", 23456,123)(rohan is object)
     
     rohan.phone_number
     23456
    
   Q4. Why self is used in OOPs?
     ans.self-function,method-self is first parameter-used in oops to define method in class
         self is used -bind variable in class,self is reference for passing data in class


   Q5. What is inheritance? Give an example for each type of inheritance.
   ans.inheritance allows us to define a class that inherits all the methods and properties from another class. 
       Parent class is the class being inherited from, also called base class. 
       Child class is the class that inherits from another class, also called derived class.
    example
     
     class test :
    
    def test_meth(self):
        return "this is my first class "
    class child_test(test):
    pass
    child_test_obj = child_test()
    child_test_obj.test_meth()
    this is my first class
    
   multi label inheritance,multple inheritance
        
     class glint :
    def product_glint(self) :
        return"good"
     class glint1(glint):
    def product_gint1(self) :
        return"bad"
    class glint2(glint1) :
    pass
    obj_glin2 = glint2()
    obj_glin2.product_gint1()
    ;bad'
   
   

