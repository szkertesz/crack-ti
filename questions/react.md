# React Interview Questions & Answers

## Table of Contents

| No.  | Questions                                                                                           | Priority |
|------|-----------------------------------------------------------------------------------------------------|----------|
|      | Core React                                                                                      | HIGH     |
| 1    | [What is React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-react)                                                                                      | HIGH     |
| 2    | [What are the major features of React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-major-features-of-react)                                                               | HIGH     |
| 3    | [What is JSX?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-jsx)                                                                                        | HIGH     |
| 3.1  | [Is it possible to use react without JSX?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#is-it-possible-to-use-react-without-jsx)                                                            | HIGH     |
| 4    | [What is the difference between Element and Component?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-element-and-component)                                               | HIGH     |
| 5    | [How to create components in React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-create-components-in-react)                                                                  | HIGH     |
| 6    | [When to use a Class Component over a Function Component?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#when-to-use-a-class-component-over-a-function-component)                                            | LOW      |
| 7    | [What are Pure Components?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-pure-components)                                                                           | MEDIUM   |
| 7.1  | [If Pure Component is better from the optimization point of view, why don't we use it by default?(#)(https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#if-pure-component-is-better-from-the-optimization-point-of-view-why-dont-we-use-it-by-default) ]| MEDIUM   |
| 8    | [What is state in React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-state-in-react)                                                                             | HIGH     |
| 9    | [What are props in React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-props-in-react)                                                                            | HIGH     |
| 10   | [What is the difference between state and props?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-state-and-props)                                                     | HIGH     |
| 11   | [Why should we not update the state directly?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#why-should-we-not-update-the-state-directly)                                                        | HIGH     |
| 11.1 | [Is the state updated synchronously?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#is-the-state-updated-synchronously)                                                                 | HIGH     |
| 12   | [What is the purpose of callback function as an argument of setState()? ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-purpose-of-callback-function-as-an-argument-of-setstate)                             | MEDIUM   |
| 13   | [What is the difference between HTML and React event handling?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-html-and-react-event-handling)                                       | LOW      |
| 14   | [How to bind methods or event handlers in JSX callbacks?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-bind-methods-or-event-handlers-in-jsx-callbacks)                                             | HIGH     |
| 15   | [How to pass a parameter to an event handler or callback?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-pass-a-parameter-to-an-event-handler-or-callback)                                            | HIGH     |
| 16   | [What are synthetic events in React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-synthetic-events-in-react)                                                                 | HIGH     |
| 17   | [What are inline conditional expressions?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-inline-conditional-expressions)                                                            | MEDIUM   |
| 18   | [What is "key" prop and what is the benefit of using it in arrays of elements?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements)                       | HIGH     |
| 19   | [What is the use of refs?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-use-of-refs)                                                                            | HIGH     |
| 20   | [How to create refs?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-create-refs)                                                                                 | HIGH     |
| 20.1 | [Difference between "createRef" and "useRef"(#) ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#difference-between-createref-and-useref)                                                     | MEDIUM   |
| 21   | [What are forward refs?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-forward-refs)                                                                              | MEDIUM   |
| 22   | [React.memo VS useMemo ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#reactmemo-vs-usememo)                                                                              | HIGH     |
| 23   | [How do you memoize a component?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-do-you-memoize-a-component)                                                                     | HIGH     |
| 24   | [What is Virtual DOM?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-virtual-dom)                                                                                | HIGH     |
| 25   | [How Virtual DOM works?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-virtual-dom-works)                                                                              | HIGH     |
| 26   | [What is the difference between Shadow DOM and Virtual DOM?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-shadow-dom-and-virtual-dom)                                          | HIGH     |
| 27   | [What is React Fiber?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-react-fiber)                                                                                | HIGH     |
| 28   | [What is the main goal of React Fiber?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-main-goal-of-react-fiber)                                                               | HIGH     |
| 29   | [What are controlled components?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-controlled-components)                                                                     | MEDIUM   |
| 30   | [What are uncontrolled components?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-uncontrolled-components)                                                                   | MEDIUM   |
| 30.1 | [Controlled Uncontrolled VS Uncontrolled inputs.](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#controlled-uncontrolled-vs-uncontrolled-inputs)                                                     | MEDIUM   |
| 31   | [What is the difference between createElement and cloneElement?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-createelement-and-cloneelement)                                      | LOW      |
| 32   | [What is Lifting State Up in React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-lifting-state-up-in-react)                                                                  | HIGH     |
| 33   | [What are the different phases of component lifecycle?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-different-phases-of-component-lifecycle)                                               | HIGH     |
| 34   | [What are the lifecycle methods of React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-lifecycle-methods-of-react)                                                            | HIGH     |
| 35   | [What are Higher-Order components?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-higher-order-components)                                                                   | HIGH     |
| 36   | [How to fetch data with React Hooks?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-fetch-data-with-react-hooks)                                                                 | HIGH     |
| 37   | [What is context?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-context)                                                                                    | HIGH     |
| 38   | [What is children prop?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-children-prop)                                                                              | HIGH     |
| 39   | [What is prop drilling?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-prop-drilling)                                                                              | MEDIUM   |
| 40   | [What is the purpose of using super constructor with props argument?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-purpose-of-using-super-constructor-with-props-argument)                                 | LOW      |
| 41   | [What is reconciliation?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-reconciliation)                                                                             | HIGH     |
| 42   | [How do you conditionally render components?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-do-you-conditionally-render-components)                                                         | HIGH     |
| 43   | [What are error boundaries in React v16 ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-error-boundaries-in-react-v16)                                                             | HIGH     |
| 44   | [What are hooks?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-hooks)                                                                                     | HIGH     |
| 44.1 | [React hooks rules ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#react-hooks-rules)                                                                                  | HIGH     |
| 45   | [Why React uses className over class attribute?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#why-react-uses-classname-over-class-attribute)                                                      | LOW      |
| 46   | [What are fragments?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-fragments)                                                                                 | HIGH     |
| 47   | [Why fragments are better than container divs?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#why-fragments-are-better-than-container-divs)                                                       | HIGH     |
| 48   | [What are portals in React?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-portals-in-react)                                                                          | MEDIUM   |
| 49   | [What are stateless components?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-stateless-components)                                                                      | MEDIUM   |
| 50   | [What are stateful components?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-stateful-components)                                                                       | MEDIUM   |
|      | React Redux                                                                                     | HIGH     |
| 51   | [What is Flux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-flux)                                                                                       | HIGH     |
| 52   | [What is Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-redux)                                                                                      | HIGH     |
| 52.1 | [What hooks does Redux have ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-hooks-does-redux-have)                                                                         | HIGH     |
| 53   | [What are the core principles of Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-core-principles-of-redux)                                                              | HIGH     |
| 54   | [What are the downsides of Redux compared to Flux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-downsides-of-redux-compared-to-flux)                                                   | HIGH     |
| 56   | [What is the difference between mapStateToProps() and mapDispatchToProps()? ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops)                         | LOW      |
| 57   | [Can I dispatch an action in reducer?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#can-i-dispatch-an-action-in-reducer)                                                                | HIGH     |
| 58   | [How to access Redux store outside a component?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-access-redux-store-outside-a-component)                                                      | HIGH     |
| 59   | [What are the drawbacks of MVW pattern ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-drawbacks-of-mvw-pattern)                                                              | MEDIUM   |
| 60   | [Are there any similarities between Redux and RxJS?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#are-there-any-similarities-between-redux-and-rxjs)                                                  | MEDIUM   |
| 61   | [How to dispatch an action on load?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-dispatch-an-action-on-load)                                                                  | MEDIUM   |
| 62   | [How to use `connect` from React Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-use-connect-from-react-redux)                                                              | MEDIUM   |
| 63   | [How to reset state in Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-reset-state-in-redux)                                                                        | MEDIUM   |
| 64   | [Whats the purpose of at symbol in the redux connect decorator?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#whats-the-purpose-of-at-symbol-in-the-redux-connect-decorator)                                      | LOW      |
| 65   | [What is the difference between React context and React Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-react-context-and-react-redux)                                       | HIGH     |
| 66   | [Why are Redux state functions called reducers?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#why-are-redux-state-functions-called-reducers)                                                      | MEDIUM   |
| 67   | [How to make AJAX request in Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-make-ajax-request-in-redux)                                                                  | MEDIUM   |
| 68   | [Should I keep all component's state in Redux store?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#should-i-keep-all-components-state-in-redux-store)                                                 | HIGH     |
| 69   | [What is the proper way to access Redux store?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-proper-way-to-access-redux-store)                                                       | HIGH     |
| 70   | [What is the difference between component and container in React Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-difference-between-component-and-container-in-react-redux)                              | MEDIUM   |
| 71   | [What is the purpose of the constants in Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-purpose-of-the-constants-in-redux)                                                      | HIGH     |
| 72   | [What are the different ways to write mapDispatchToProps()? ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-different-ways-to-write-mapdispatchtoprops)                                         | MEDIUM   |
| 73   | [What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()? ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-use-of-the-ownprops-parameter-in-mapstatetoprops-and-mapdispatchtoprops)           | MEDIUM   |
| 74   | [How to structure Redux top level directories?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-structure-redux-top-level-directories)                                                       | MEDIUM   |
| 75   | [What is redux-saga?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-redux-saga)                                                                                 | LOW      |
| 76   | [What is the mental model of redux-saga?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-mental-model-of-redux-saga)                                                             | LOW      |
| 77   | [What are the differences between call and put in redux-saga ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-differences-between-call-and-put-in-redux-saga)                                        | LOW      |
| 78   | [What is Redux Thunk?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-redux-thunk)                                                                                | MEDIUM   |
| 79   | [What are the differences between redux-saga and redux-thunk ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-differences-between-redux-saga-and-redux-thunk)                                        | LOW      |
| 80   | [What is Redux DevTools?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-redux-devtools)                                                                             | LOW      |
| 81   | [What are the features of Redux DevTools?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-features-of-redux-devtools)                                                            | LOW      |
| 82   | [What are Redux selectors and Why to use them?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-redux-selectors-and-why-to-use-them)                                                       | LOW      |
| 83   | [What is Redux Form?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-redux-form)                                                                                 | LOW      |
| 84   | [What are the main features of Redux Form?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-main-features-of-redux-form)                                                           | LOW      |
| 85   | [How to add multiple middlewares to Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-add-multiple-middlewares-to-redux)                                                           | LOW      |
| 86   | [How to set initial state in Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-set-initial-state-in-redux)                                                                  | MEDIUM   |
| 87   | [How Relay is different from Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-relay-is-different-from-redux)                                                                  | LOW      |
| 88   | [What is an action in Redux?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-an-action-in-redux)                                                                         | HIGH     |
|      | React Router                                                                                    | HIGH     |
| 89   | [What is React Router?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-react-router)                                                                               | HIGH     |
| 89.1 | [What hooks does React Router have ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-hooks-does-react-router-have)                                                                  | HIGH     |
| 90   | [How React Router is different from history library?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-react-router-is-different-from-history-library)                                                 | HIGH     |
| 91   | [What are the \<Router> components of React Router v4?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-are-the-router-components-of-react-router-v4)                                               | MEDIUM   |
| 92   | [What is the purpose of push and replace methods of history?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#what-is-the-purpose-of-push-and-replace-methods-of-history)                                         | MEDIUM   |
| 93   | [How do you programmatically navigate using React router v4?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-do-you-programmatically-navigate-using-react-router-v4)                                         | MEDIUM   |
| 94   | [How to get query parameters in React Router v4 ](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-get-query-parameters-in-react-router-v4)                                                     | MEDIUM   |
| 95   | [Why you get "Router may have only one child element" warning?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#why-you-get-router-may-have-only-one-child-element-warning)                                       | MEDIUM   |
| 96   | [How to pass params to history.push method in React Router v4?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-pass-params-to-historypush-method-in-react-router-v4)                                       | MEDIUM   |
| 97   | [How to implement default or NotFound page?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-implement-default-or-notfound-page)                                                          | MEDIUM   |
| 98   | [How to get history on React Router v4?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-get-history-on-react-router-v4)                                                              | MEDIUM   |
| 99   | [How to perform automatic redirect after login?](https://github.com/szkertesz/crack-ti/blob/main/questions/react.md#how-to-perform-automatic-redirect-after-login)                                                      | MEDIUM   |

## Core React

### What is React?
### What are the major features of React?
### What is JSX?
### Is it possible to use react without JSX?
### What is the difference between Element and Component?
### How to create components in React?
### When to use a Class Component over a Function Component?
### What are Pure Components?
### If Pure Component is better from the optimization point of view, why don't we use it by default?(#) 
### What is state in React?
### What are props in React?
### What is the difference between state and props?
### Why should we not update the state directly?
### Is the state updated synchronously?
### What is the purpose of callback function as an argument of setState()? 
### What is the difference between HTML and React event handling?
### How to bind methods or event handlers in JSX callbacks?
### How to pass a parameter to an event handler or callback?
### What are synthetic events in React?
### What are inline conditional expressions?
### What is "key" prop and what is the benefit of using it in arrays of elements?
### What is the use of refs?
### How to create refs?
### Difference between "createRef" and "useRef"(#) 
### What are forward refs?
### React.memo VS useMemo 
### How do you memoize a component?
### What is Virtual DOM?
### How Virtual DOM works?
### What is the difference between Shadow DOM and Virtual DOM?
### What is React Fiber?
### What is the main goal of React Fiber?
### What are controlled components?
### What are uncontrolled components?
### Controlled Uncontrolled VS Uncontrolled inputs.
### What is the difference between createElement and cloneElement?
### What is Lifting State Up in React?
### What are the different phases of component lifecycle?
### What are the lifecycle methods of React?
### What are Higher-Order components?
### How to fetch data with React Hooks?
### What is context?
### What is children prop?
### What is prop drilling?
### What is the purpose of using super constructor with props argument?
### What is reconciliation?
### How do you conditionally render components?
### What are error boundaries in React v16 
### What are hooks?
### React hooks rules 
### Why React uses className over class attribute?
### What are fragments?
### Why fragments are better than container divs?
### What are portals in React?
### What are stateless components?
### What are stateful components?

## React Redux

### What is Flux?
### What is Redux?
### What hooks does Redux have 
### What are the core principles of Redux?
### What are the downsides of Redux compared to Flux?
### What is the difference between mapStateToProps() and mapDispatchToProps()? 
### Can I dispatch an action in reducer?
### How to access Redux store outside a component?
### What are the drawbacks of MVW pattern 
### Are there any similarities between Redux and RxJS?
### How to dispatch an action on load?
### How to use `connect` from React Redux?
### How to reset state in Redux?
### Whats the purpose of at symbol in the redux connect decorator?
### What is the difference between React context and React Redux?
### Why are Redux state functions called reducers?
### How to make AJAX request in Redux?
### Should I keep all component's state in Redux store?
### What is the proper way to access Redux store?
### What is the difference between component and container in React Redux?
### What is the purpose of the constants in Redux?
### What are the different ways to write mapDispatchToProps()? 
### What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()? 
### How to structure Redux top level directories?
### What is redux-saga?
### What is the mental model of redux-saga?
### What are the differences between call and put in redux-saga 
### What is Redux Thunk?
### What are the differences between redux-saga and redux-thunk 
### What is Redux DevTools?
### What are the features of Redux DevTools?
### What are Redux selectors and Why to use them?
### What is Redux Form?
### What are the main features of Redux Form?
### How to add multiple middlewares to Redux?
### How to set initial state in Redux?
### How Relay is different from Redux?
### What is an action in Redux?

## React Router

### What is React Router?
### What hooks does React Router have 
### How React Router is different from history library?
### What are the \<Router> components of React Router v4?
### What is the purpose of push and replace methods of history?
### How do you programmatically navigate using React router v4?
### How to get query parameters in React Router v4 
### Why you get "Router may have only one child element" warning?
### How to pass params to history.push method in React Router v4?
### How to implement default or NotFound page?
### How to get history on React Router v4?
### How to perform automatic redirect after login?