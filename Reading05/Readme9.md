
The submissions for this assignment are posts in the assignment's discussion. Below are the discussion posts for rahaf bedas, or you can view the full discussion.

from Read: Linked Lists
6 hours ago
rahaf bedas
linked lists 

are fundamental data structure used in computer science  to store and manage collection of data they consist of nodes each node has a data inside it and a pointer pointing to the location of the next node. 

analogy (train of wagons)

think of the linked list as a train of wagons >> nodes each wagon has cargo >> data and reference to the next wagon the last wagon is linked to nothing (null) this shows the end of the train. 

wagon (node) >> wagon (node) >>wagon (node) >> wagon (node) >> null 

cargo is the data inside the wagon (node) it could be String,object,int.
next this is the link that connects the wagon to the next it has memory address to the next wagon in the train.
null at the end of the train the last wagons next points at nothing which is null referring to the end of the linked list.
 

why linked lists 

linked lists are beneficial because they  have dynamic memory they can extend or shrink easily allowing insertion and deletion  unlike arrays they have fixed sizes and elements are stored contagious memory locations. 

How to implement

to implement linked lists there's a need for a (node) class with two fields one to the cargo and another for the reference to the next node also there will be a need for methods to add, delete and traverse through the list. 

class Node {

object data; 

Node Next; 

Node(object data) {

this.data = data;

this.next = null;}

} 

class LinkedList {

Node Head;}

 

Quiz 

create a class named (node) that has two fields (data,next), create a class named (LinkedList) with one field (Head) and methods to (insert) a new node at the end of the linked list and a method to (Display) the linked list . in the main class create a linked list insert (10,20,30) and display.

vocabulary definition list 

1. linked list : a linear data structure consisting of collection of elements called (node)  where each node has data and a pointer to the next node in sequence.

2. node : is an individual element  of a linked list that holds data and pointer to the next node .

3. data: are the information stored in node it can be any data type.

4. pointer : it's a connection from one node to the next node in sequence indicating to the order of the list.

5. Head : the first node in the linked list it's the starting point of the list.

6. Tail : is the last node of the list and it's pointer points at null meaning the list has ended.

7. singly linked list : is a type of linked list which has one pointer pointing at the next node in the list.

8.douply linked list : is a type of linked list which has 2 pointers one for the next node and one for the previous node. 

9. insertion: the process of adding a new node to the end of the linked list, updating pointer, and adjusting the order.

10. deletion: the process of deleting a node it envolv updating the pointer tp bypass the deleted node.

11. null : a special value that indicated the absence of pointer used to tell that the list has ended.

cheat sheet

linked lists basics : 

  - linear data structure.     - consists of nodes. 

- each node has value and pointer to the next node

-Head : first node - Tail : last node.

Node : 

- contain value and pointer     

  Types of linked lists : 

-singly   - doubly  -circular  

- Insertion: adding a new node to the list and updating the pointers

- deletion : removing a node from the list and updating the pointer

Time complexity : 

- insert at beginning o(1)   end o(n) 

- deletion at beginning o(1)   end o(n)

- search o(n ) 

null : 

end of the linked list 

Diagram 

Head >> [value | next] --> [value | next] --> [value | next] --> null 

 Anthropomorphize the concepts

 

Nina the Node: Hey there, Liam! It's always nice to see you connecting us nodes together.

Liam the Link: Thanks, Nina! I'm here to keep you all linked up and in the right order.

Lila the List: Hello, you two! It's wonderful to see the teamwork. Liam, you're like the bridge that connects each of Nina's friends.

Nina the Node: Absolutely, Lila! And we each carry a little piece of data with us, like personal treasures.

Liam the Link: That's right, Nina. And Lila helps keep everything organized and guides us along the way.

Lila the List: Indeed, Liam! Just like a train, you all form a sequence. Nina, you're the first wagon in the train. What a responsibility!

Nina the Node: Oh, it's an honor, Lila! Being the head of this chain means I'm the one to greet everyone who comes along.

Liam the Link: And I'm here to make sure every wagon knows where to go next. It's like giving directions in a big city!

Lila the List: Liam, you're the navigator we can't do without. Nina, as we add more wagons, each one gets to meet you and find its place.

Nina the Node: It's like forming a chain of friendship, one wagon at a time. I make sure everyone feels welcomed!

Liam the Link: And I ensure that friendships continue smoothly as each wagon knows exactly who comes after them.

Lila the List: What a fantastic team you make! Nina, your enthusiasm is infectious, and Liam, your reliability is unmatched.

Nina the Node: Thanks, Lila! And Liam, you're the true unsung hero, guiding us through the journey.

Liam the Link: It's all for the greater good of keeping connections strong and data flowing smoothly.

Lila the List: Well said, you two! Remember, as long as we stay linked and work together, we'll keep this joyful train of data moving forward.

Nina the Node: Count on it, Lila! Our adventure continues, one node and one link at a time.

 

map of information 

Linked Lists
│
├─ Basics
│  ├─ Linear data structure
│  ├─ Nodes with data and reference
│  ├─ Head: First node
│  ├─ Tail: Last node
│
├─ Node
│  ├─ Contains data and reference
│  ├─ Analogous to a wagon in a train
│
├─ Types
│  ├─ Singly Linked List (unidirectional)
│  ├─ Doubly Linked List (bidirectional)
│  ├─ Circular Linked List (last points to first)
│
├─ Operations
│  ├─ Insertion (add new node)
│  ├─ Deletion (remove node)
│  ├─ Traversal (move through list)
│
├─ Advantages
│  ├─ Dynamic size
│  ├─ Efficient insertions/deletions
│
├─ Disadvantages
│  ├─ More memory overhead (references)
│  ├─ Slower random access compared to arrays
│
├─ Time Complexity (Average)
│  ├─ Insertion: O(1) beginning, O(n) end
│  ├─ Deletion: O(1) beginning, O(n) end
│  ├─ Search: O(n)
│
├─ Memory Management
│  ├─ Dynamic memory allocation
│
├─ Pointer Arithmetic
│  ├─ Manipulate memory addresses
│
├─ Null Reference
│  ├─ End of list indicated by null
│
├─ Circular Linked List
│  ├─ Last node links back to first
│
├─ Tail Reference Optimization
│  ├─ Store reference to last node
│
├─ Doubly Linked List
│  ├─ Nodes have next and previous references
│
├─ Big O Notation
│  ├─ Describes algorithm complexity
│
├─ Time Complexity (Worst Case)
│  ├─ Insertion: O(n)
│  ├─ Deletion: O(n)
│  ├─ Search: O(n)

 

fill- in - the -blank worksheet 

 

1. A ________________ is a linear data structure consisting of nodes.
2. Each ________________ holds both actual ________________ and a ________________ to the next node.
3. The ________________ points to the first node in a linked list.
4. The last node in a linked list usually points to ________________.
5. A ________________ linked list has unidirectional references.
6. In a ________________ linked list, each node has next and previous references.
7. A ________________ linked list forms a circular structure.
8. ________________ allows memory allocation as needed, making linked lists flexible.
9. ________________ and ________________ are common operations on linked lists.
10. Moving from one node to another is known as ________________.
11. ________________ is the process of adding a new node to a linked list.
12. ________________ is the process of removing a node from a linked list.
13. The ________________ of linked lists can result from storing references.
14. The ________________ of insertion at the beginning of a linked list is O(1).
15. The ________________ of insertion at the end of a linked list is O(n).
16. The ________________ of searching in a linked list is O(n).
17. The end of a linked list is indicated by a ________________ reference.

Answers:
1. Linked List
2. Node, Data, Reference
3. Head
4. Null
5. Singly
6. Doubly
7. Circular
8. Dynamic
9. Insertion, Deletion
10. Traversal
11. Insertion
12. Deletion
13. Memory Overhead
14. Time Complexity
15. Time Complexity
16. Time Complexity
17. Null


 

 

 

 

 

 

