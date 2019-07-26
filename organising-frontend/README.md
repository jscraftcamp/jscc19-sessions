# the fractured front-end - divide and conquer and fuck up?

_session by Sebastian_

(Organising Front-End Components on the schedule)

Sebastian told us from his experience about how they split it:

- specific component<br />These deal with specific use cases.
- product/project component?<br />A component that is specific to a
  product/project.
- generic component<br />A mistake could be that such a component deals with a
  very specific input. That should not happen and should go into the "specific
  component" or "product/project component".

Translations could be done by having some kind of contract, use a translation
service "give me a string"

Short side about Atomic Design:

1. Atoms - Single use case component
2. Molecules - Component using multiple Atoms
3. Organisms - Combined Molecules

About the tree structure: "I do not look it up in the file tree, because it's
too big"

Carlos brought up an idea that they use a tree which can be seen as the UI tree.
If you reuse some component, it moves up into a generic component. Otherwise,
the deeper you are in the tree, the more specific it gets. If you remove a
component by deleting a directory, you can be pretty sure to have all dead code
removed.
