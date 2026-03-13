Usually, when you suspend processes, you'll want to resume them at some point.
Otherwise, why not just terminate them?
To resume processes, your shell provides the `fg` command, a builtin that takes the suspended process, resumes it, and puts it back in the foreground of your terminal.

Go try it out!
This challenge's `run` needs you to suspend it, then resume it.
Good luck!

Note: fg takes an argument of job ID with a leading "%" symbol. Jobs can be seen by running `jobs` command.
