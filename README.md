# Uncommon HTML and JavaScript Error Handling
This repository demonstrates two scenarios resulting in uncommon errors in HTML and JavaScript interaction.  The first involves gracefully handling a non-existent attribute retrieval, while the second showcases the consequences of operating on a null element.  The solutions highlight how to prevent unexpected behavior.

## Bugs

* **Non-Existent Attribute:** Attempting to retrieve a non-existent attribute from a DOM element returns `null` without throwing an error, potentially causing unexpected application behavior.
* **Null Element Method Call:**  Calling a method on a `null` element (an element that does not exist) results in a runtime error.