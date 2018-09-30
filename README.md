# AngularDart+Flutter RX BLoC App Starter

**Objective** Create an AngularDart/Flutter app starter/scaffold that adheres to the BLoC (Business Logic Component) design guidelines, uses Reactive Programming, and promotes code sharing.

## Approach
- use BLoC design guidelines
- streams / sinks
- stream builders
- stream controllers
- flutter code sharing

## BLoC Design Guidelines
- inputs / outputs are simple streams / sinks
- dependencies must be injectable
- dependencies must be platform agnostic (works on angular & flutter)
- no platform branching allowed (no "if flutter" or "if angular")

## UI Design Guidelines
- every complex component should have corresponding BLoC
- components should send inputs "as is"
- components should show output as close as possible to "as is"
- all branching should be based on simple BLoC boolean outputs

