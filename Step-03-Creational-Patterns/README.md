## Step 3 – Creational Design Patterns

### Why Creational Patterns
- Control object creation
- Reduce tight coupling
- Improve flexibility and testability

### Patterns Covered

#### Singleton
- Ensures only one instance
- Prefer DI-managed singleton in ASP.NET Core
- Avoid for stateful classes

#### Factory Method
- Centralizes object creation
- Removes if-else logic
- Uses interfaces and polymorphism

#### Abstract Factory
- Factory of factories
- Creates families of related objects

#### Builder
- Builds complex objects step by step
- Improves readability

#### Prototype
- Creates objects by cloning
- Useful when creation is expensive
