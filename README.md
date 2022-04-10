# pass_dart

abstract class Animal {
    void printName();
    void printSound();
}

class Dog extends Animal {
  @override
  void printName(){
    print ("Name is dog");
  }
  
  @override
  void printSound() {
    print("Sound is Bark");
  } 
}

class Cat extends Animal {
  @override
  void printName(){
    print ("Name is cat");
  }
  
  @override
  void printSound() {
    print ("Sound is miaow");
  }
}

class Cow extends Animal {
  @override
  void printName(){
    print ("Name is cow");
  }
  
  @override
  void printSound() {
    print ("Sound is moo");
    
  }
}
  
void main()
{
   Dog dog = Dog();
   Cat cat = Cat();
   Cow cow = Cow();
  
   print("Dog:\n"); 
     dog.printName() ;
     dog.printSound();
   print("\nCat:\n"); 
     cat.printName() ;
     cat.printSound(); 
   print("\nCow:\n"); 
     cow.printName() ;
     cow.printSound();
}
