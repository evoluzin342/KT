
# Architecture patterns around angular

  
## Keyword

- [Store]- manage business data and state  
- [Reducer]- Reducers are the functions that know what to do with a given action and the previous state of your app.  
- [View] - a hierarchical composition of React components   
- [Actions] -events created from user events that triggered on the View  
- [Dispatcher] - an event bus for all actions

###### Every Application contains two layers. 

- [View layer]- render the view based on the data we have in controller.
- [service layer and also known as the data layer] - fetch the data from the database and update the data in the controller  


## How should we design the service layer ?

####  How should we structure the service layer ?

#### In this  we can discuss NgRx,Flux pattern.

# What about NgRx Store pattern ?

  - [NgRX store](https://github.com/evoluzin342/ngrx/blob/master/README.md) - Ngrx is a set of Angular libraries for reactive extensions.
     ### Included
     - [@ngrx/store](https://github.com/ngrx/store) - RxJS powered state management for Angular apps, inspired by Redux
     - [@ngrx/effects](https://github.com/ngrx/effects) - Side effect model for @ngrx/store
     - [@angular/router](https://github.com/angular/angular) - Angular Router
     - [@ngrx/db](https://github.com/ngrx/db) - RxJS powered IndexedDB for Angular apps
      - [@ngrx/store-devtools](https://github.com/ngrx/store-devtools) - Instrumentation for @ngrx/store enabling time-travel debugging
      
 #  What about Flux pattern?
 
  - [Flux pattern](https://github.com/evoluzin342/Flux-pattern) - Flux is a pattern for unidirectional data flows Actions encapsulate events Dispatcher is a central hub that holds callbacks Stores hold app state Many implementations


## Refernces

### `Angular vs react:`

- [Forms](https://blog.angular-university.io/introduction-to-angular-2-forms-template-driven-vs-model-driven/) -

- [Change Detection](https://blog.angular-university.io/how-does-angular-2-change-detection-really-work/) -

- [Unidirectional Data Flow](https://blog.angular-university.io/angular-2-what-is-unidirectional-data-flow-development-mode/) -

- [Performance 1](https://medium.com/paramsingh-66174/catalysing-your-angular-4-app-performance-9211979075f6) -

- [Performance 2](https://github.com/mgechev/angular-performance-checklist) -

- [ZoneJS](https://blog.thoughtram.io/angular/2017/02/21/using-zones-in-angular-for-better-performance.html) -
 
- [a](https://rubygarage.org/blog/react-vs-angularjs) -

- [b](https://hackernoon.com/angular-vs-react-the-deal-breaker-7d76c04496bc) -

- [c](https://www.cleveroad.com/blog/react-vs-angular-ultimate-performance-research-2017) -


- [d](https://www.pluralsight.com/guides/front-end-javascript/angular-vs-react-a-side-by-side-comparison) -

- [e](https://www.sitepoint.com/react-vs-angular/) -

- [f](https://da-14.com/blog/reactjs-vs-angular-comparison-which-better) -

- [g](https://www.toptal.com/front-end/angular-vs-react-for-web-development) -

- [h](https://www.quora.com/Is-React-killing-Angular) -

- [i](https://www.codementor.io/chrisharrington/react-vs-angularjs-vs-knockoutjs-a-performance-comparison-85hwzepbz) -

### `Uni direction topic`

- [a](https://medium.com/@AdamRNeary/unidirectional-data-flow-yes-flux-i-am-not-so-sure-b4acf988196c) -

- [b](https://www.tamtam.nl/en/reactivity-state-and-a-unidirectional-data-flow/) -

- [c](https://stackoverflow.com/questions/33447710/mvc-vs-flux-bidirectional-vs-unidirectional)) -

### `AOT`

- [a](https://angular.io/guide/aot-compiler) )) -

- [b](http://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/)) -

- [c](https://angular-2-training-book.rangle.io/handout/aot/) -

- [d](https://stackoverflow.com/questions/41450226/angular-2-just-in-time-jit-vs-ahead-of-time-aot-compilation) -

- [e](https://objectpartners.com/2017/04/14/ahead-of-time-compilation-with-angular/) -

- [f](https://hacks.mozilla.org/2017/02/a-crash-course-in-just-in-time-jit-compilers/) -


### `NgRX store`

- [Redux & ngRx](https://blog.angular-university.io/angular-2-redux-ngrx-rxjs/) -

- [ngRx Store](https://blog.angular-university.io/angular-ngrx-store-and-effects-crash-course/) -

- [example-1](https://www.toptal.com/angular-js/ngrx-angular-reaction-application) -

- [example-2](https://github.com/ngrx/platform/tree/master/example-app)-


### `Flux pattern`

- [What is Flux](http://fluxxor.com/what-is-flux.html) -

- [understanding-flux-pattern](https://softwareengineering.stackexchange.com/questions/295119/understanding-flux-pattern) -
 
- [example-1](https://github.com/ngrx/platform/tree/master/example-app) -

### `Observables`
- [overview](http://reactivex.io/documentation/observable.html) -

- [observable-](http://reactivex.io/documentation/observable.html) -


### `RxJS`

- [overview](http://reactivex.io/rxjs/manual/overview.html) -

- [rxjs](https://blog.angular-university.io/functional-reactive-programming-for-angular-2-developers-rxjs-and-observables/) -

- [Common Issues](https://blog.angular-university.io/how-to-build-angular2-apps-using-rxjs-observable-data-services-pitfalls-to-avoid/) -

- [Debugging](https://blog.angular-university.io/debug-rxjs/) -

- [rxjs-observables-observers-operators](https://toddmotto.com/rxjs-observables-observers-operators)-

- [introduction-observables-angular-developers](https://developer.telerik.com/topics/web-development/introduction-observables-angular-developers/) -

- [rx-book](https://xgrommx.github.io/rx-book/why_rx.html) -

- [observable](http://jsclass.jcoglan.com/observable.html) -

- [rxjs-functions-with-examples](https://www.sitepoint.com/rxjs-functions-with-examples/) -









