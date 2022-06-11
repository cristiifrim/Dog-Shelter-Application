##Dog shelter application

---

This is a university project that I had to make for the OOP course.
Initially the application could've been used by a console-based UI. In the last assignments, I was asked to implement a graphical user interface using the QT framework.

This application is based on two users: Administrator and User.

---

**An administrator can do the following:**

- Add a new dog in the shelter. If a dog with the same name exists, the operations fails.
- Remove a dog from the shelter. If the name searched is not in the repository, the operation fails.
- Update a dog's data. If the name of the dog is not found, the operation fails.
- See all dogs in the shelter. 

Last operation is done with a QListView from the QT framework.

There is undo/redo possibility for the last performed operation. This is done either by pressing the buttons or using CTRL+Z, CTRL+Y.

**A user is able to do these operations:**

- See all the dogs from the shelter one by one.
If the user likes the dog, he can select the adopt option which adds the dog in the adoption list.
If he is not satisfied with the current dog, the user can press the next button, which shows the next dog from the repository.
- See all dogs that respect a breed-age filter. The user has the same operations as above.
- See the adoption list.
- Display the adoption list in the chosen format.

When the application starts, the user needs to chose between administrator mode or user mode. If user mode is selected, the user is asked to choose how to save his adoption list [HTML/CSV].

If the Display operation is selected, the adoption list is opened in the correct application:
- Browser(Google Chrome) for HTML
- Notepad for CSV

If the user adopts a dog by accident, he can undo(redo) the operation by using CTRL+Z(CTRL+Y).

---

## Requirements
- **Microsoft Visual Studio 2022**
- **QT Framework**
