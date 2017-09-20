# ProjectOne
personNeedOne

**注意**：菜单需要设置高度，关于菜单高度：
1. `MATCH_PARENT`，自动适应Item高度，保持和Item一样高，比较推荐;
2. 指定具体的高，比如80;
3. `WRAP_CONTENT`，自身高度，极不推荐;

## Item侧滑菜单
<image src="./xq-1.gif" width="320px"/>

### 侧滑删除和拖拽
拖拽和侧滑删除的功能默认关闭的，所以先要打开功能：
```java
recyclerView.setLongPressDragEnabled(true); // 开启拖拽。
recyclerView.setItemViewSwipeEnabled(true); // 开启滑动删除。
```
