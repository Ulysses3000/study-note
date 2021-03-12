study react note


+ 所有的状态都在 state 里面当 state 一更新 是不是就是所有的订阅者都要抖一抖

+ 如果 和vuex一样分module 那订阅的时候怎么写，如何组织模块间的关系

+ combineReducers 就是进行module封装的 解决第二个，第一个问题还存在，一个dispatch 全局所有的订阅会不会抖动
