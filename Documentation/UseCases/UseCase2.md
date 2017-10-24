# KBNR-UC-2: Open and edit a Kanban board

## Summary

The user can expand a kanban board they have created and loaded and edit its properties.

## Rationale

A user wants to change a kanban board's attributes, but this cannot be done if the user cannot find a link to the properties first. A kanban board can be expanded in order to change its settings and see and move cards inside it. When the kanban board is expanded, the user may decide to change its properties. This can be done by clicking on "Edit" inside the board. From here, the user can look over the board's settings and change them individually. Finally, the user may save his/her changes or discard them.

## Preconditions

A kanban board is visible in the application.

## Users

All users

## Events

1. The user clicks on a Kanban board to expand it.
2. The board expands to show its cards and categories.
3. The user clicks on a Kanban board's "Edit" option.
4. A pop-up displays the Kanban board's properties.
5. The user selects a property and enters a value for that property.
6. The user exits the property and clicks "Save changes".
7. The pop-up closes.

## Alternate Events

1. If the user doesn't want to modify the board's properties in step 5, he/she clicks "Cancel" to exit the pop-up.
2. If the user made an invalid change in step 5, the pop-up displays a message telling him/her that his/her answer was invalid and why.
3. If the user wants to discard his/her changes, he/she clicks "Cancel" to do so.

## Post-conditions

A kanban board's properties and contents are saved.