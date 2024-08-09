# vue学习记录

## 2024-08-07

1. Make sure to apply all app configurations before mounting the app!
1. Multiple application instances for server render

## 2024-08-08

1. Functions called inside binding expressions will be called every time the component updates, so they should not have any side effects, such as changing data or triggering asynchronous operations.
1. ref vs reactive:what's the diffrence.
1. don't mutate other state, make async requests, or mutate the DOM inside a computed getter!
1. The key binding expects primitive values - i.e. strings and numbers. 