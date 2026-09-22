# Js-DataStructure's

Array - Object - Set - Map - Stack - Queue's - Linked Lists -  Hash Table - Tree's - Graph's

### A walkthrough Demo using every Day a Datastructure

# 01- Array
```
An ordered list of values, where each value has a numbered position (starting at 0), so you can grab any item instantly if you know its position.

Official (MDN): Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed.

Types:

Regular Array — holds any data type, most common
Multidimensional Array — an array of arrays, used for grids/matrices e.g. [[1,2],[3,4]]
Typed Array — fixed-type, fixed-length, used for raw binary data (Int32Array, Float64Array) — rare in everyday web dev
```

# 02 - Objects
```
A container that stores data as labeled pairs — a name (key) attached to a value — so instead of remembering "the 3rd item," you look things up by name, like user.name or user.age.

Official (MDN): An object is a collection of properties, and a property is an association between a name and a value.

Types:

Plain Object — the standard { key: value } used constantly
Map — see 04-Map, an object-like structure with any-type keys
WeakMap — like Map, but keys must be objects and get garbage-collected automatically when unreferenced elsewhere
```

# 03 - Set
```
A list where every value can only appear once — if you try to add something that's already there, it's just ignored. Great for removing duplicates or checking "have I seen this before?"

Official (MDN): The Set object lets you store unique values of any type. A value in the set may only occur once — it is unique in the set's collection.

Types:

Set — the standard version, holds any value type
WeakSet — only holds objects (not primitives), and those objects can be garbage-collected if nothing else references them
```

# 04 - Map
```
A container like Object, but built specifically for key-value pairs — except keys can be ANY type (an object, a function, a number, not just strings), and it keeps track of insertion order reliably, plus tells you its size directly.

Official (MDN): The Map object holds key-value pairs and remembers the original insertion order of the keys. Any value (both objects and primitive values) may be used as either a key or a value.

Types:

Map — the standard version
WeakMap — same as Map, but keys must be objects, entries garbage-collected automatically when unreferenced — used for memory-safe metadata attachment
```

# 05 - Stack
```
A pile of items where you can only add or remove from the top — like a stack of plates. The last thing you put on is the first thing you take off (LIFO - Last In, First Out).

Official (NIST): A stack is a data structure where the most recently added element is the first one removed.

Types : (by implementation, not distinct variants) 

Array-based Stack — simplest, uses push/pop on a normal array
Linked-List-based Stack — uses nodes with pointers, avoids potential resizing costs of arrays
```

# 06 - Queue
```
A line of people waiting — whoever joined first gets served first. You add to the back, remove from the front (FIFO - First In, First Out).

Official (NIST): A queue is a FIFO structure — the first element added is the first one removed.

Types:

Simple Queue — standard FIFO, add at back, remove from front
Circular Queue — fixed-size queue that wraps around to the start instead of wasting freed-up space
Priority Queue — items come out based on priority, not arrival order (e.g. hospital ER) — often built using a Heap
Deque (Double-Ended Queue) — can add/remove from BOTH ends, not just front/back separately
```

# 07 - Linked List
```
A chain of items where each item just knows where the NEXT one is. Unlike an array, the items aren't sitting next to each other in memory — they're scattered around, connected only by these "next" pointers.

Official (NIST): A linear collection of nodes, each pointing to the next, where order is given by pointers rather than physical position in memory.

Types:

Singly Linked List — each node points only to the NEXT node
Doubly Linked List — each node points to both NEXT and PREVIOUS — allows backward traversal, costs extra memory per node
Circular Linked List — the last node points back to the first, forming a loop instead of ending at null
```

# 08 - Hashe Table
```
A super-fast lookup system — you give it a key (like a name), it runs that key through a formula to instantly know where to find (or store) the matching value, so you skip searching item-by-item. This is actually what powers JS Objects and Maps under the hood.

Official (NIST): A hash table maps keys to values using a hash function, which computes an index into an array of buckets where the value is stored.

Types : Comming Soon
```

# 09 - Tree
```
A branching structure that starts at one root and splits into children, like a family tree or a folder/subfolder system — each item (except the root) has exactly one parent.

Official (NIST): A connected, acyclic graph with one designated root node, where every other node has exactly one parent.

Types:

Binary Tree — each node has at most 2 children
Binary Search Tree (BST) — a binary tree where left child < parent < right child, enabling fast search
Balanced BST (AVL Tree, Red-Black Tree) — self-balancing versions of a BST so search stays fast after lots of insertions/deletions
Heap (Min-Heap / Max-Heap) — every parent is smaller (min) or bigger (max) than its children — used to build priority queues
Trie (Prefix Tree) — specialized for storing strings, each root-to-node path represents a prefix — used in autocomplete/search suggestions
N-ary Tree — a general tree where nodes can have more than 2 children (e.g. a folder structure)
```

# 10 - Graph
```
A network of points (nodes) connected by lines (edges) — no strict hierarchy like a tree, connections can go any direction and even loop back. Think social networks, maps, flight routes.

Official (NIST): A set of vertices connected by edges, which may be directed or undirected, weighted or unweighted — trees are actually a special case of graphs.

Types : Comming Soon
```
