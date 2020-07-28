# Design Patterns
###### Design Patterns for Software Engineering

## Strategy Pattern

### When to use the Strategy Pattern?

1. When you want to define a class that will have one behavior that is similar to other behaviors in a list
   * I want the class object to be able to choose from
     - Not Flying
     - Fly with Wings
     - Fly Super Fast
2. When you need to use one of several behaviors dynamically
3. Often reduces long lists of conditionals
4. Avoids duplicate code
5. Keeps class changes from forcing other class changes
6. Can hide complicated / secret code from the user
7. Negative: Increased Number of Objects / Classes


### UML Diagram for Strategy Pattern
  ![Strategy Pattern](img/StrategyPatternUML.png)
