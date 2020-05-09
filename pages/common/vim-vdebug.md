# vim vdebug

> Multi-language DBGP debugger client for Vim (PHP, Python, Perl, Ruby, etc.)
> https://github.com/vim-vdebug/vdebug

- Step over

`<F2>`

- Step into

`<F3>`

- Step out

`<F4>`

- Start/run (to next breakpoint/end of script)

`<F5>`

- Stop debugging (kills script)

`<F6>`

- Detach script from debugger

`<F7>`

- Run to cursor

`<F9>`

- Toggle line breakpoint

`<F10>`

- Show context variables (e.g. after "eval")

`<F11>`

- Evaluate variable under cursor

`<F12>`

- Set a breakpoint of any type (see :help VdebugBreakpoints)

`:Breakpoint <type> <args>`

- Evaluate some code and display the result

`:VdebugEval <code>`

- Evaluate the expression under visual highlight and display the result

`<Leader>e`
