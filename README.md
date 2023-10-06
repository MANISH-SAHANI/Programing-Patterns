# Game programming patterns in Unity

<h1 align="center" ><img src="https://github.com/MANISH-SAHANI/Unity-Programing-Patterns/assets/91081774/09003df5-ee71-477e-927f-9cf54979bcc7" alt="Logo" width="550" /></h1>


Here you can find a collection of programming (design) patterns in Unity, mainly from the book [Game Programming Patterns](http://gameprogrammingpatterns.com). These are very useful to better organize your Unity project as it grows because they capture best practices and solutions to commonly occuring problems. You don't have to use them - you should see them as tools in your toolbox. You can also experiment with how they are implemented to fit your specific needs. Some patterns, such as Update, Game Loop, Component, are already built-in into Unity so you are already using them! 

Programming patterns can be divided into the following groups:
1. **Architectural patterns.** One example is the MVC (Model-View-Controller).
2. **Design patterns.** Are more specific than architectural patterns, such as the Singleton.
3. **Anti-patterns.** Are a collection of patterns programmers are using to solve problems even though they shouldn't use them because they are ineffective solutions. One example is a "God object," most likely called GameController where you collect everything you might need to make the game work. The problem with such as class is that it will grow in size, which will make it more difficult to maintain, and it will also be difficult to debug because the code doesn't belong together.  

Patterns from the book Game Programming Patterns:

1. [Command](_text/1-command.md)
2. [Flyweight](_text/2-flyweight.md)
3. [Observer](_text/3-observer.md)
4. [Prototype](_text/4-prototype.md)
5. [Singleton](_text/5-singleton.md)
6. [State](_text/6-state.md)
7. [Double Buffer](_text/7-double-buffer.md)
8. [Game Loop](_text/8-game-loop.md)
9. [Update Method](_text/9-update-method.md)
10. [Bytecode](_text/10-bytecode.md)
11. [Subclass Sandbox](_text/11-subclass-sandbox.md)
12. [Type Object](_text/12-type-object.md)
13. [Component](_text/13-component.md)
14. [Event Queue](_text/14-event-queue.md)
15. [Service Locator](_text/15-service-locator.md)
16. [Data Locality](_text/16-data-locality.md)
17. [Dirty Flag](_text/17-dirty-flag.md)
18. [Object Pool](_text/18-object-pool.md)
19. [Spatial Partition](_text/19-spatial-partition.md)

Other patterns:

20. [Decorator](_text/20-decorator.md)
21. [Factory](_text/21-factory.md)
22. [Facade](_text/22-facade.md)
23. [Template](_text/23-template.md)

Note that these are not all patterns out there. I recently read a book called "Machine Learning Design Patterns" which includes even more design patterns with a focus on machine learning problems. But I will continue adding patterns as I find them and if they are related to game development.  
