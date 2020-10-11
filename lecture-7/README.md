# Quick Note on LinkedList

- To get the last node when iterating using the while loop use
  ```
  while node.link is not None:
    node = node.link
  
  ```


  - To get the n-1 node when iterating using the while loop with n being the last node use
  ```
  while node.link.link is not None:
    node = node.link
  
  ```
  This is used in situation when you have to delete the last item. You have to stand on the last but one node and unlink the last item. ie. setting the link to None.

# DoublyLinkedList
### [video](https://www.loom.com/share/9e55f65b49454fa68bbe27555b102e72)