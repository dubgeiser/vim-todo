===============
README vim-todo
===============

Enables fast creation of 'tick-off' bullet lists:

    [ ] A new item/task
    [V] Task done
    [X] Task canceled


Example mapping::

    nmap <Leader>o :call Todo_ToggleTickbox()<cr>
    vmap <Leader>o :call Todo_ToggleTickbox()<cr>
    nmap <Leader>v :call Todo_TickFinished()<cr>
    vmap <Leader>v :call Todo_TickFinished()<cr>
    nmap <Leader>x :call Todo_TickCancelled()<cr>
    vmap <Leader>x :call Todo_TickCancelled()<cr>

With this mapping, following keystrokes manage the todo list::

    ,o creates (or removes) the [ ] mark.
    ,v ticks a box created with ,o as "done" [V]
    ,x ticks a box as canceled [X]

