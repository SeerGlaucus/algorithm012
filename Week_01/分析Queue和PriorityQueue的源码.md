### Queue

队列的核心方法有3个，offer、pull、peek，它的子类AbstractQueue实现了另3个方法，add、remove、element，这三个方法只是对前面3个的封装，如果返回失败则抛出异常。

它的实现有：

* LinkedList
* ArrayBlockingQueue
* LinkedBlockingQueue
* PriorityQueue

等。

### PriorityQueue

数组 + 堆排序，保持数组第一个元素为优先级最高元素，插入和删除时，重新调整堆，使它重新满足堆的特性。