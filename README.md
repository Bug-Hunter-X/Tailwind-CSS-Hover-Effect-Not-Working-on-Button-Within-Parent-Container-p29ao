# Tailwind CSS Hover Effect Bug

This repository demonstrates an uncommon bug in Tailwind CSS where a hover effect on a button doesn't work when the button is inside a parent container with a background color set.

## Bug Description

The hover effect on the button in `bug.jsx` is not working as expected.  The background color of the button remains unchanged on hover. This seems to occur only when the button is within a parent div with a background color defined in Tailwind.

## Bug Solution

The `solution.jsx` file demonstrates the solution.  Adding the `!important` flag to the hover class overrides the parent container's styling, resolving the issue.