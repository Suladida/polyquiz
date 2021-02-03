# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
> "Many forms". Having, taking, or passing through many different forms or stages.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
> IS-A Relationship. When a parent (super) class is used to refer to a child class. E.G. A parent class of MythicalCreatures having child classes of Unicorn, Vampire, etc... They will have identical properties (species, diet, origin, etc), the values of which can be changed / overwritten to suit each subclass.

3. What can we use to implement polymorphism in Java?
> Create a super class which is abstract and have subclasses extend from them.

4. How many 'forms' can an object take when using polymorphism?
> I'm not sure what is meant by the word **"form"** - sorry! It's own form or the form of it's super (parent) class? i.e. A Unicorn is a Mythical Creature AND a Unicorn. 

5. Give an example of when you could use polymorphism.
> When creating the Mythical Creatures (outlined above).



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
> HAS-A relationship. It allows a class to be made that references one or more objects from other classes using instance variables.


7. When would you use composition? Provide a simple example in Java.
> When multiple classes are going to share methods / behaviours. 
> e.g. Unicorns and Vampires would both have legs. Leg could be a class in itself which is implemented by Unicorn and Vampire to give them their legs. 

8. What is/are the advantage(s) of using composition? 
> You can reuse existing code and keep things tidy.

9. When an object is destroyed, what happens to all the objects it is composed of?
> If they are not used anywhere else then they are removed from memory