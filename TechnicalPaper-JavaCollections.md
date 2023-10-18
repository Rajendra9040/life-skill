###  Java Collections
<br>
In Java, the java.util package provides a framework of classes and interfaces for working with collections of objects. The core interface in this framework is the Collection interface. There are several classes that implement the Collection interface or extend other collection-related classes. Here are some of the key classes that implement the Collection interface or are closely related to collections in Java:<br>

<br>
ArrayList: ArrayList is one of the most commonly used classes in Java. It implements the List interface, which extends the Collection interface. ArrayList is an ordered collection that allows duplicate elements and provides dynamic sizing.
<br>
<br>
LinkedList: LinkedList also implements the List interface. It is implemented as a doubly-linked list, which allows for efficient insertions and deletions at both ends of the list.
<br>
<br>
HashSet: HashSet implements the Set interface, which extends the Collection interface. It is a collection that does not allow duplicate elements and does not guarantee the order of elements. It uses a hash table for storage.
<br>
<br>
LinkedHashSet: LinkedHashSet is similar to HashSet, but it maintains the order of elements as they were inserted.
<br>
<br>
TreeSet: TreeSet is another implementation of the Set interface. It stores elements in a sorted order (based on their natural order or a specified comparator).
<br>
<br>
HashMap: HashMap implements the Map interface and is not a direct implementation of the Collection interface. However, it is often used in conjunction with collections for key-value mappings. It uses hash tables to store key-value pairs.
<br>
<br>
LinkedHashMap: Similar to HashMap, LinkedHashMap maintains the order of elements based on their insertion order.
<br>
<br>
TreeMap: TreeMap is an implementation of the Map interface that stores key-value pairs in a sorted order based on the keys.
<br>
<br>
Vector: Vector is an older class that predates the Java Collections Framework but still implements the List interface. It is synchronized and thread-safe.
<br>
<br>
Stack: Stack is a subclass of Vector and represents a last-in, first-out (LIFO) stack data structure.
<br>


## Some other important data structure that does not implement Collections Interface but implement Map Interface. 


<br>
HashMap:

HashMap is one of the most commonly used Map implementations. It uses a hash table for storage and provides constant-time average complexity for basic operations (e.g., get and put).
It does not guarantee any specific order of key-value pairs.
<br>
<br>
LinkedHashMap:

LinkedHashMap is an extension of HashMap that maintains the order of elements according to their insertion order. It provides predictable iteration order.
<br>
<br>
TreeMap:

TreeMap is a Map implementation that stores its elements in a sorted tree structure. It maintains the keys in sorted order, allowing for efficient range queries and key-based operations.
Keys must be comparable or provided with a custom Comparator.
<br>
<br>
Hashtable:

Hashtable is an older version of a hash table-based Map. It is thread-safe (synchronized) but less efficient than HashMap.
It's considered somewhat obsolete, and it's recommended to use HashMap or other newer alternatives.
<br>
<br>
ConcurrentHashMap:

ConcurrentHashMap is a thread-safe Map implementation that allows high concurrency. It is optimized for multi-threaded environments, providing efficient concurrent access to key-value pairs.
It is often used in multi-threaded and high-performance scenarios.
<br>
<br>
EnumMap:

EnumMap is a specialized Map that is designed for use with enum keys. It provides high performance and type safety when working with enum keys.
<br>

