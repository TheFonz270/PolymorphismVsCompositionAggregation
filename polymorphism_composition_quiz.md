# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
    "Many""change"

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
    That subclasses should be able to work as if implemented as one of it's parent classes, essentially the parent can't do anything the child can't do.

3. What can we use to implement polymorphism in Java?
    Inheritance and interfaces.

4. How many 'forms' can an object take when using polymorphism?
    In theory it's not limited.

5. Give an example of when you could use polymorphism.
    assign different types of output hardware one interface so they can all be included in one arrayList by a computer class even though they still all have their individual classes.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
    focusing on the "componants" that make up the object being defined within the class, the objects can't exist without the class.

7. When would you use composition? Provide a simple example in Java.
    when you don't want an classes objects/attributes existing outside of the class. maybe a component of the house is the walls and the roof. but if you remove the house the walls and roof are gone as well.

8. Give a difference between composition and aggregation?
    In aggregation objects exist outside of the classes they are used in, in composition they only exist within the class. Composition = IS_PART_OF, Aggregation = HAS_A

9. What is/are the advantage(s) of using composition/aggregation?
    Stops us from getting bogged down in over complicated inherritance trees, implementing attributes or methods we possibly don't even need.
    

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
    they are destroyed as well.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
    they still exist independently from the destroyed object.