| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | QueueTaskOptions |

# &#10025; Initializer

```ts
{
  
  /**

* The number of milliseconds to wait before queueing the task.
*
* NOTE: just like `setTimeout`, there is no guarantee that the task will actually run
* after the specified delay. It is merely a *minimum* delay.
*
* Defaults to `0`
  */
  delay?: number;
  
  /**

* If `true`, the task will be run synchronously if it is the same priority as the
* `TaskQueue` that is currently flushing. Otherwise, it will be run on the next tick.
*
* Defaults to `false`
  */
  preempt?: boolean;
  
  /**

* If `true`, the task will be added back onto the queue after it finished running, indefinitely, until manually canceled.
*
* Defaults to `false`
  */
  persistent?: boolean;
  
  /**

* If `true`, the task will be kept in-memory after finishing, so that it can be reused for future tasks for efficiency.
*
* Defaults to `true`
  */
  reusable?: boolean;
}
```