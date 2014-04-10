This web component flattens the text of its own content and exposes this as an
attribute which can be bound to.

Elements often need to convert the content of distributed nodes into a value
which can be passed to a sub-element via binding. This element makes that
possible in a declarative fasion. For example, suppose an element wants to
pass its own distributed content to a sub-element called interesting-element:
