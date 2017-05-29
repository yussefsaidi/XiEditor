# XiEditor
Prototype similar to ViEditor

Text Editor with the following possibilities :

C++ keywords are highlighted in blue.

Initial Mode: 
   - "dd" delete a line you're pointing to
   - "x" deletes a character you're pointing to
   - Naviguate the text with ( j = down, k = up, L = right, H = Left)
   - "u" to undo the previous action (and prior)
   
Insert Mode:
   - "i" (lower case) to insert a char in current line
   - "I" (upper case) to insert a new line 
   - Press Enter to confirm the current input to insert
   
   
   Linked List used to store the actual text (Iterators needed to make the traversal more efficient).
   Stack used for the undo function.
   BST used to highlight the C++ keywords in your text in blue.
