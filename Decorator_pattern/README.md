# Decorator Pattern

The Decorator Pattern attaches additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality.

In this project we used Beverage as the subject (main entity)
 * Created several types of beverages extending Beverage (DarkRoast, Espresso, HouseBlend)
 * Used CondimentDecorator to extend (not using inheritance per se but just to conform to the same type of class as Beverage) Beverage. This is basically condiment decorator wrapping around beverage.
 * Created different types of condiments which extend the CondimentDecorator. Passed the beverage object to the constructor so that we can build upon the given beverage's properties (Ex: add cost to the existing cost).