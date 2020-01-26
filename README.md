
# Highlevel Test-Plan:

 1) Open dropdown menu list and expand the first arrow
 - Validate that elements indeed dropdown from the list after we expand it by clicking the narrow-down.     
 
Expected: List expanded; 'Node 2' is visible


2) Open dropdown menu list and expand the first arrow-down
Select 'Node 2' from the second list 
Try selecting one more 'Node 1' node straight away.

Expected: List collapsed; 'Node 1' is NOT visible


3) Open dropdown menu list and expand the first and the second arrow-down to expand all lists
- Select every note one after another and validate the path appeared in the main field corresponds to the selected node.

Expected: Path is corresponding to the node selected


4) Open dropdown menu list and expand the first arrow-down to release the first list.

- Validate that 'Node 2' is available after we expanded the first list.

Expand the second arrow-down to release the second list.

- Validate that all nodes from 3-9 are available for to be selected.

Collapse the second list.

- Validate that all nodes from 3-9 are now unavailabe for to be selected and not visible .

- Validate that 'Node' is still available for to be selected and  visible .

Collapse the first list.

- Validate that 'Node 2' is now unavailable to be selected and is not visible.


Expected: Expand/Collapse functionality is working correctly and releases the relevant list


5) Open dropdown menu list and expand the first arrow-down to release the first list.

Select 'Node 2' as it is a part of the first dropdown list and has children.

- Validate that after selection the valid node path appeared in the main field.

Open dropdown again.

- Validate that the dropdown list structure remain untouch and the list neither collapsed nor expanded by checking visibility of nodes above and abscence underneath 'Node 2'.

Expected: Selection of the node only selects it and doesn't change the dropdown list structure

6) Open dropdown menu list.

Click the 'cancel' button.

- Validate than nodes are not visible anymore from dropdown as well as the 'cancel' button .

Expected: Cancel closes the dropdown 

7) Open dropdown menu list
Select the first node.

Click the 'clear' button.

- Validate that main fiesld is empty.

Expected: Clear button clears the selection.

