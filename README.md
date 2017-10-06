
# Architecture patterns around angular

-Every Application contains two layers. 

- [View layer]- render the view based on the data we have in controller.
- [service layer and also known as the data layer] - fetch the data from the database and update the data in the controller  


## How should we design the service layer ?

#### Should we use a store concept?

#### We can use the patterns?

#### In this session we can discuss NgRx,Flux pattern.

  - [NgRX store](https://github.com/evoluzin342/ngrx) - Ngrx is a set of Angular libraries for reactive extensions.
     ### Included
     - [@ngrx/store](https://github.com/ngrx/store) - RxJS powered state management for Angular apps, inspired by Redux
     - [@ngrx/effects](https://github.com/ngrx/effects) - Side effect model for @ngrx/store
     - [@angular/router](https://github.com/angular/angular) - Angular Router
     - [@ngrx/db](https://github.com/ngrx/db) - RxJS powered IndexedDB for Angular apps
      - [@ngrx/store-devtools](https://github.com/ngrx/store-devtools) - Instrumentation for @ngrx/store enabling time-travel debugging
 
  - [Flux pattern](https://github.com/evoluzin342/Flux-pattern) - Flux is a pattern for unidirectional data flows Actions encapsulate events Dispatcher is a central hub that holds callbacks Stores hold app state Many implementations
  
## Keyword

- [Stores]- manage business data and state  
- [Reducer]- Reducers are the functions that know what to do with a given action and the previous state of your app.  
- [View] - a hierarchical composition of React components   
- [Actions] -events created from user events that triggered on the View  
- [Dispatcher] - an event bus for all actions

## Refernces

https://blog.angular-university.io/angular-2-redux-ngrx-rxjs/

https://www.toptal.com/angular-js/ngrx-angular-reaction-application

https://github.com/ngrx/platform/tree/master/example-app

https://softwareengineering.stackexchange.com/questions/295119/understanding-flux-pattern

