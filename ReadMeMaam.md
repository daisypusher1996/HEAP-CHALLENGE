Submission by:
Kiele Andrei Remendado (@blueberry1980)
& Joshua A. Ecat (@daisypusher1999)
from BSCS - 2A

• Title: The Keeper's Magical Heap Quest
• Theme: Organize a collection of magical artifacts by their power levels using heaps for quick access and retrieval!

• Learning Goals
1. Understand Heaps: Learn how Max-Heap and Min-Heap structures work, their properties, and how they can be implemented using arrays.
2. Heap Operations: Gain practical knowledge of inserting elements, removing the root, and re-heapifying while maintaining heap properties.
3. Algorithmic Thinking: Understand heapify-up and heapify-down processes, which are crucial in maintaining the structure during dynamic changes.
4. Practical Applications: Explore how heaps can be used in real-life applications such as priority queues and inventory management.
5. Debugging and Output Interpretation: Learn to interpret and debug intermediate steps through clear, descriptive outputs.

• Tasks:
1. Insert artifacts with their power levels into a Max-Heap and display the heap after each addition.
2. Remove the most powerful artifact from the heap and re-heapify.
3. Transform a random collection of artifact power levels into a properly structured Max-Heap.

• Instructions:
1. Heap Type Selection:
The program allows the user to manage either a Max-Heap (default) or a Min-Heap. This is controlled by the isMaxHeap flag.
~ Set isMaxHeap = true for Max-Heap (strongest artifact on top).
~ Set isMaxHeap = false for Min-Heap (weakest artifact on top).
2. Task 1: Insert Elements
~ Add elements (artifact power levels) to the heap using insertElement.
~ Observe the updated heap after each insertion to understand how the heap maintains its property.
3. Task 2: Remove Root
~ Remove the root (most or least powerful artifact based on heap type) using removeRoot.
~ The heap will re-heapify to maintain its structure after removal.
4. Task 3: Heapify a Random Array
~ Convert a random array into a valid heap using the heapify function.
~ Observe the transformation of an unsorted array into a structured heap.
5. Run the Program:
~ Compile and run the program using  a C++ compiler (e.g., g++).
~ Follow the outputs for intermediate results and explanations of each operation.

• Input:
~ Artifact power levels (e.g., [50, 30, 70, 20, 40]).
• Output:
~ Heap after each insertion (e.g.,
 > After inserting 50: [50]
 > After inserting 30: [50, 30]
 > After inserting 70: [70, 30, 50]).
~ Heap after removing the root (70): [50, 30, 40, 20]).
~ Heapified array after converting a random list into a Max-Heap (e.g., [60, 40, 20, 15, 10]).

• Grading Rubric:
~ Functionality (10 points): Correct implementation of heaps.
~ Creativity (5 points): Fun theme and clear outputs.
~ Code Clarity (5 points): Well-documented and organized code.
