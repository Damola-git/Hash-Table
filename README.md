# Hash Table 

## Overview  
This repository provides a custom implementation of a hash table data structure in JavaScript. Hash tables are widely used for efficient data storage and retrieval, offering an average time complexity of O(1) for most operations.  

## Features  
- **Customizable Hashing Function:** Replaceable hashing logic to suit specific use cases.  
- **Collision Resolution:** Supports separate chaining (linked lists) for handling hash collisions.  
- **Dynamic Resizing:** Automatically resizes the table for optimal performance.  
- Fully written in JavaScript (ES6+), with clean, modular, and well-documented code.  


### Supported Methods  
- **`set(key, value)`**: Adds or updates a key-value pair.  
- **`get(key)`**: Retrieves the value associated with a key.  
- **`delete(key)`**: Removes a key-value pair.  
- **`has(key)`**: Checks if the hash table contains a key.  
- **`keys()`**: Returns all keys in the hash table.  
- **`values()`**: Returns all values in the hash table.  

## Implementation Details  
- **Hashing Function**: A simple hash function that converts keys to numeric indices within the table size.  
- **Collision Handling**: Separate chaining with linked lists for robust collision management.  
- **Resizing**: Automatically doubles the size when the load factor exceeds 0.75.  

## Testing  
Run the unit tests to verify functionality:  


Let me know if you'd like to add specific details or further customize the documentation!
