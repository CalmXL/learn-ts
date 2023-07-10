# 组件 -> commit-> mutation state -> 视图变更 -> 响应式

1. 组件 -> dispatch -> action
2. dispatch -> type(actionType) -> 某一个 action 
3. action -> commit 调用 -> mutation 
4. mutation -> change -> state
5. render 方案：state