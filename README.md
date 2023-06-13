# Python-basic-file
from abc import ABC, abstractmethod
class  Animal(ABC):
    @abstractmethod
    def make_sound(self):
        pass
    def eat(self):
        print("i am eating")

class Dog(Animal):
    def make_sound(self):
        print("dog barking")

class Cat(Animal):
    def make_sound(self):
        print("meow meow")

class snake(Animal):
    def make_sound(self):
        print("hiss hiss")


d1 = Dog()
d1.eat()
d1.make_sound()
c= Cat()
c.make_sound()
