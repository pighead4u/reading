# vue学习记录

## 2024-08-07

1. Make sure to apply all app configurations before mounting the app!
1. Multiple application instances for server render

## 2024-08-08

1. Functions called inside binding expressions will be called every time the component updates, so they should not have any side effects, such as changing data or triggering asynchronous operations.
1. ref vs reactive:what's the diffrence.
1. don't mutate other state, make async requests, or mutate the DOM inside a computed getter!
1. The key binding expects primitive values - i.e. strings and numbers. 

## 2024-08-09

### vue

1. Note that locally registered components are not also available in descendant components.
1. vue-route:
    1. 通过 useRouter() 和 useRoute() 来访问路由器实例和当前路由
    1. `params` 不能与 `path` 一起使用，`name`可以

### TypeScript
1. https://juejin.cn/post/7344282440725577765--Type和Interface的区别


## 2024-08-12
