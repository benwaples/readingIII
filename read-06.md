# Summary of reading for Class 06

## [Redis](https://aws.amazon.com/redis/)
Remote Dictionary Server is a fast in-memory key-value data store. Stores all data in-memory and not on disks or SSDs. Which results in really fast data searches.

Often used for caching, chat, gaming, sessions store, geospatial, machine learning, and real-time analytics.

## [Queue](https://www.educative.io/edpresso/what-is-a-queue)
Data structure placing elements in sequence similar to a stack. First in, first out => first task in the stack will be the first task executed.

## [Task Queue](https://redislabs.com/ebook/part-2-core-concepts/chapter-6-application-components-in-redis/6-4-task-queues/)
A specific tasks queuer?? not sure

## [Redis FIFO](https://aws.amazon.com/redis/)
redis does FIFO, LIFO, and priority queues.

This stuff is like SQL queries?? But less english.

You can set priorities on tasks. Doesn't read too well.

## [Bull Quick Start](https://optimalbits.github.io/bull/)
Queues are a way to handle a ton of tasks quickly, Bull is a simpler way to use redis. Making the complex calls simple.

* Bull is a class that is used to create queues. `const queue = new Bull('my-first-queue')`

* producers add jobs/tasks to the queue.

* consumers processes jobs/tasks. When idle, the process method will be called and do something.

* listeners are just a way to be notified when a tasks is processed.

* naming jobs is a thing which helps with clean code and readability.

### Job Types
1. FIFO - first in first out
2. LIFO - list in first out
3. Delayed - jobs can be added to the queue and be delayed before being processed.
4. prioritized - jobs can be prioritized over other jobs.
5. repeatable - jobs that repeat a number of times.