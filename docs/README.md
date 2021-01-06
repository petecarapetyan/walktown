# January 5 transitional status

- this is very preliminary, experimental
- for specific demo of problem with something I did on rocket nav in the `with-sidebar` pages

## Additional TLDR stuff for further conversation

- What is the general direction?
- Comments on status
- Invitation for comments

## What is the general direction?

- I have 18 different "themes" that are grid-area-layouts based on sizing from popular sites such as IBM.com or wired.com or Axios.com or ...
- Colors and surrogate content can be added in to match theme
- Idea is to be able to "swap" any theme in and out while still leaving 90% of the `includes/partial/yada.njk` files as is.
- Attempting to "decouple" whatever aspect of theming that would prevent that swap, without doing a wholesale replace that would end up being 80% copypaste of existing.

## Comments on status

- going very slow because learning CSS nuances as I go.
- also the decoupling is taking time because some stuff is either not functional yet or in most cases it's just taking me time to understand what does what
- the general design can't just be "done" it needs to be super clean and understandable else no-one will even try to mess with the themes and improve and/or use them
- the grid-area-layout part is working much better than I anticipated. So that is positive

## Invitation for comments

- as if you had nothing better to do..
- anyway, feel free to comment