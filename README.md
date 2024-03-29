# [go back to overview](https://github.com/c4arl0s#ios-apps-using-swiftuikit)

In order to update an existing Git submodule execute: (You might need permissions from Owner to get submodules)

```console
 git submodule update --remote --merge
```

# [Guided Project: List (ToDoListApp)](https://github.com/c4arl0s/GuidedProjectList#guided-project-list-todolistapp---content-1)

Display, add, delete and save a list of tasks.

| Notes                                                                                                                         | Code                                                                                                                          | Diagrams                                                                                                                      | xproj                                                                                                                         |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://user-images.githubusercontent.com/24994818/124356297-e0743e00-dbda-11eb-8b24-3bdc502de604.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124356344-1fa28f00-dbdb-11eb-84f2-4ca9de8eacb0.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124356385-67c1b180-dbdb-11eb-9f0d-0acc35cbb03f.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124356432-9475c900-dbdb-11eb-86a3-ac6c41a6f0d8.gif" width="250"> |

1. [x] [1. Project Planning](https://github.com/c4arl0s/ToDoListApp#1-project-planning)
    - [x] [Features](https://github.com/c4arl0s/ToDoListApp#--features)
    - [x] [Workflow](https://github.com/c4arl0s/ToDoListApp#--workflow)
    - [x] [Controllers](https://github.com/c4arl0s/ToDoListApp#--controllers)
    - [x] [Views](https://github.com/c4arl0s/ToDoListApp#--views)
    - [x] [Models](https://github.com/c4arl0s/ToDoListApp#--models)
2. [x] [2. Set up Project and Display Models](https://github.com/c4arl0s/ToDoListApp#2-set-up-project-and-display-models)
    - [x] [Define the Model](https://github.com/c4arl0s/ToDoListApp#--define-the-model)
    - [x] [Configure the Table View Controller](https://github.com/c4arl0s/ToDoListApp#--configure-the-table-view-controller)
    - [x] [Supply Initial Data](https://github.com/c4arl0s/ToDoListApp#--supply-initial-data)
3. [x] [3. Add and Delete Controls](https://github.com/c4arl0s/ToDoListApp#3-add-and-delete-controls)
    - [x] [Add Items](https://github.com/c4arl0s/ToDoListApp#--add-items)
    - [x] [Delete Items](https://github.com/c4arl0s/ToDoListApp#--delete-items)
4. [x] [4. Static Table View Interface](https://github.com/c4arl0s/ToDoListApp#4-static-table-view-interface)
    - [x] [Save and Cancel Buttons](https://github.com/c4arl0s/ToDoListApp#--save-and-cancel-buttons)
    - [x] [Basic Information](https://github.com/c4arl0s/ToDoListApp#--basic-information)
    - [x] [Due Date](https://github.com/c4arl0s/ToDoListApp#--due-date)
    - [x] [Notes](https://github.com/c4arl0s/ToDoListApp#--notes)
    - [x] [Additional Controls](https://github.com/c4arl0s/ToDoListApp#--additional-controls)
5. [x] [Connect the Static Table View to Code](https://github.com/c4arl0s/ToDoListApp#5-connect-the-static-table-view-to-code)
    - [x] [Add a Table View Controller Subclass](https://github.com/c4arl0s/ToDoListApp#--add-a-table-view-controller-subclass)
    - [x] [Disable the Save Button](https://github.com/c4arl0s/ToDoListApp#--disable-the-save-button)
    - [x] [Dismiss Keyboard on Return](https://github.com/c4arl0s/ToDoListApp#--dismiss-keyboard-on-return)
    - [x] [Switch Button Image](https://github.com/c4arl0s/ToDoListApp#--switch-button-image)
    - [x] [Update Date Label](https://github.com/c4arl0s/ToDoListApp#--update-date-label)
    - [x] [Update the Date Picker Starting Value](https://github.com/c4arl0s/ToDoListApp#--update-the-date-picker-starting-value)
    - [x] [Expand and Collapse the Date Picker cell](https://github.com/c4arl0s/ToDoListApp#--expand-and-collapse-the-date-picker-cell)
6. [x] [6. Create and Save the model](https://github.com/c4arl0s/ToDoListApp#6-create-and-save-the-model)
    - [x] [Read Data from Controls](https://github.com/c4arl0s/ToDoListApp#--read-data-from-controls)
    - [x] [Pass Data Across the Unwind Segue](https://github.com/c4arl0s/ToDoListApp#--pass-data-across-the-unwind-segue)
7. [x] [7. Editing Details](https://github.com/c4arl0s/ToDoListApp#7-editing-details)
    - [x] [Present Details via Push](https://github.com/c4arl0s/ToDoListApp#--present-details-via-push)
    - [x] [Update the Static Table View Controller](https://github.com/c4arl0s/ToDoListApp#--update-the-static-table-view-controller)
    - [x] [Update the Unwind Segue Logic](https://github.com/c4arl0s/ToDoListApp#--update-the-unwind-segue-logic)
8. [x] [8. Create a Custom UITableViewCell](https://github.com/c4arl0s/ToDoListApp#8-create-a-custom-uitableviewcell)
    - [x] [Create a Cell Subclass](https://github.com/c4arl0s/ToDoListApp#--create-a-cell-subclass)
    - [x] [Design the Cell](https://github.com/c4arl0s/ToDoListApp#--design-the-cell)
    - [x] [Add a Cell Delegate Method](https://github.com/c4arl0s/ToDoListApp#--add-a-cell-delegate-method)
9. [x] [9. Codable](https://github.com/c4arl0s/ToDoListApp#9-codable)
    - [x] [Add Support for Archiving and Unarchiving](https://github.com/c4arl0s/ToDoListApp#--add-support-for-archiving-and-unarchiving)
10. [ ] [10. Wrapup](https://github.com/c4arl0s/ToDoListApp#10-wrapup)
11. [ ] [11. Stretch Goals](https://github.com/c4arl0s/ToDoListApp#11-stretch-goals)
12. [ ] [12. summary](https://github.com/c4arl0s/ToDoListApp#12-summary)
13. [x] [13. Set constraints for dueDateLabel and its location](https://github.com/c4arl0s/GuidedProjectList#13-set-constraints-for-duedatelabel-and-its-layout)
14. [x] [14. Hide text view when switch is off](https://github.com/c4arl0s/GuidedProjectList#14-hide-text-view-when-switch-is-off)

