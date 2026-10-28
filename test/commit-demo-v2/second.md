# Second fixture

| column a | column b | column c |
| --- | --- | --- |
| one | two | three |
| four | five | six |
| seven | eight | nine |

This paragraph exists so the diff mixes table rows with prose. It is long
enough to wrap in a narrow viewer, which is exactly where wrapping bugs
show up, and it mentions an unbroken token
`AReallyLongIdentifierWithoutAnySpacesInItAtAll` to catch overflow when
the surrounding container refuses to shrink.

A closing line keeps the file from ending on a code span, which some
renderers treat differently from ordinary text.
