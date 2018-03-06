**TestList:**

-The methods do the same thing for both linked lists and for array lists. They are called by the same name and just perform a little differently.

**-** TestRemoveObject **:**

- remove(5) removes the number at index 5 and moves everything else up the list.
- remove(Integer.valueOf(5) removes index number 4 in the list because the integer 5 is there. Then it moves everything else up the list.

**TestIterrator:**

-The methods do the same thing for both linked lists and array lists. They are called the same thing in linked lists and in array lists.

**-** testRemove

- If I put list.remove(Integer.valueOf(77) without the while statement and without the if statement, it only removes the first 77 in the list. If I do it only without the if, it never stops.

**TestPerformance:**

-As the size increases, array lists do better than linked lists when accessing something from the list, while linked lists perform better than array lists when adding and removing things from the list.