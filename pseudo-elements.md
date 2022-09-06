## Pseudo Elements:

represent an element in the document other than what exists in the document tree. For example, you can select the **first line of a paragraph** using the pseudo element **p::first-line** even though there is no HTML element that is wraping that line of text.


## ::marker

Selects the marker box of a list item which typically contains a bullet or a number. 
**It works only on any element or pseudo element set to**
``
display: list-item;
``

such as the ``<li>`` or ``<summary> `` elements. 
