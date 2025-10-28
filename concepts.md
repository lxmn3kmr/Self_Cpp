**STL**

**hashing** - hash functions? 
**Set** -> Unique elements, ordered (sorted order)
    Set uses **hashing** to insert elements into buckets.
    search, insertion, removal - Avg constant time complexity
Unordered Set -> not sorted order.
Unordered MultiSet -> can store duplicates. 
**MultiSet** -> can store duplicates in Sorted order. Red Black Tree. (self balanced tree) O(logn) Complexity
    Need to provide compare function to compare objects to sort. 

**Map**  -> Key Value Pair. map<Key, Value> obj_map; eg: std::map<string, int> Map;
       Key should be unique. Implemented using self balanced trees - Red Black Tree or AVL tree. O(logn) Complexity
       Stored in sorted order on basis of Key. Dictionary type of problems.
       Map.first is Key, Map.second is Value. Value can be a vector -> std::map<string, vector<int>, std::less<>> Map;
**unordered map** Unique Keys. Not sorted. uses hashing. stored in Buckets. 
**unordered multimap** allows duplicates. 

**vector** Dynamic Array or ArrayList. std::vector<int> arr; 
        Size can grow/Shrink dynamically. Size doubles once it is full. 
        In C, we use arrays for faster access and when size is known. If size is unknown we use LinkedList. 
   **Element access** -> at(), at() is exception for out of bound access, [], front() -> arr.front() is first element in array, back() -> last element, data() -> pointer of the array, 
   **Modifiers** -> arr.push_back(10), pop_back(), insert(), emplace(), emplace_back(), resize(), swap(), erase(), clear().

