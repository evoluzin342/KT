
# Architecture patterns around angular

-Every Application contains two layers. 

- [View layer]- render the view based on the data we have in controller.
- [service layer and also known as the data layer] - fetch the data from the database and update the data in the controller  


## How should we design the service layer ?

#### Should we use a store concept?

#### We can use the patterns?

#### In this session we can discuss NgRx,Flux pattern.

  - [NgRX store](https://github.com/evoluzin342/ngrx) - 
  - [Flux pattern](https://github.com/evoluzin342/Flux-pattern) - Flux is a pattern for unidirectional data flows Actions encapsulate events Dispatcher is a central hub that holds callbacks Stores hold app state Many implementations
  
## Keyword

- [Stores]- manage business data and state  
- [View] - a hierarchical composition of React components   
- [Actions] -events created from user events that triggered on the View  
- [Dispatcher] - an event bus for all actions

## Refernces

https://blog.angular-university.io/angular-2-redux-ngrx-rxjs/

https://softwareengineering.stackexchange.com/questions/295119/understanding-flux-pattern


an event bus for all actions
