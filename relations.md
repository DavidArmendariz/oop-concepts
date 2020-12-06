# Relations between objects

Apart from *inheritance* and *implementation* we have other types of relations.

## Association

It is a type of relationship in which one object uses or interacts with another.

Usually, we use it to represent something like a field in a class.

For example, we can always ask an order *for its customer*.

Or, we can indicate the presence of a method that will return an *order's customer*

![association_example](pictures/association_example.png)

## Dependency

Typically, implies that an object accepts another object as a method parameter, instantiates, or uses another object.

A dependency exists between two classes if changes to the definition of one class result in modifications in another class.

![dependency_example](pictures/dependency_example.png)

## Composition

Is a "whole-part" relationship between two objects, one of which is composed of one or more instances of the other. The component **can only exist as a part of the container**. In this case, the departments can only exist as part of the university.

![composition_example](pictures/composition_example.png)

## Aggregation

It is a less strict variant of composition, where one object contains a reference to another. The container does not control the life cycle of the component. The component can exist without the container and can be linked to several containers at the same time.

![aggregation_example](pictures/aggregation_example.png)
