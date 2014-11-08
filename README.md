In this log, there is no message 'Stopping process',
which means that `stop` hook is not executed

```shell
% bundle exec guard --debug --no-notify                                                                                         16:35:36
16:35:37 - DEBUG - Command execution: hash stty
16:35:37 - DEBUG - Guard starts all plugins
16:35:37 - DEBUG - Hook :start_begin executed for Guard::Inline
16:35:37 - INFO - Starting process
16:35:37 - DEBUG - Hook :start_end executed for Guard::Inline
16:35:37 - INFO - Guard is now watching at '/Users/ivan/code/guard_repro'
16:35:37 - DEBUG - Start interactor
16:35:37 - DEBUG - Command execution: stty -g 2>/dev/null
[1] guard(main)> exit
16:35:40 - DEBUG - Interactor was stopped or killed
16:35:40 - DEBUG - Command execution: stty  2>/dev/null
```
