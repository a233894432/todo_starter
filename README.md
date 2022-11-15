# Todo Starter

USE THIS TEMPLATE TO INIT YOUR TODO PROJECT!

**YOU NEED TO ADD SECRETS ENV(MAIL_USERNAME/MAIL_PASSWORD/MAIL_TO/MAIL_FROM) WHICH IN GITHUB SETTINGS -> ACTIONS TO MAKE EMAIL NOTIFY WORK**

# Use todo-plus-parser to generate html file
```bash
npm i todo-plus-parser -g
todo-plus-parser -i "./" -o "./out.html"
```
Then you get your doing(which you are doing now) && critical(which you think critical but not start to do) todo items and github actions will notify you everyday by email which you set.

![](assets/imgs/out.png?raw=true)


Usage
It adds 11 commands to the command palette:

```bash
    'Todo: Open' // Open or create your project's todo file
    'Todo: Open Embedded' // Open embedded todos
    'Todo: Toggle Box' // Toggle todo's box symbol
    'Todo: Toggle Done' // Toggle todo's done symbol
    'Todo: Toggle Cancelled' // Toggle todo's cancelled symbol
    'Todo: Toggle Start' // Toggle a todo as started
    'Todo: Toggle Timer' // Toggle the timer
    'Todo: Archive' // Archive finished todos
    'Todo: Embedded View - Filter' // Filter the embedded todos view
    'Todo: Embedded View - Clear Filter' // Clear the filter in the embedded todos view
    'Todo: Embedded View - Toggle View All Files' // Toggle between viewing all files or only the current one
```
It adds 6 shortcuts when editing a Todo file:

```bash
    'Cmd/Ctrl+Enter' // Triggers `Todo: Toggle Box`
    'Alt+Enter' // Triggers `Todo: Toggle Box`
    'Alt+D' // Triggers `Todo: Toggle Done`
    'Alt+C' // Triggers `Todo: Toggle Cancelled`
    'Alt+S' // Triggers `Todo: Toggle Start`
    'Cmd/Ctrl+Shift+A' // Triggers  `Todo: Archive`
```