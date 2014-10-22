pipe to utilities that dont take stdin

`git branch --list | grep "my-feature" | xargs git checkout`

[reference](http://superuser.com/questions/189362/how-to-pipe-command-output-to-other-commands)
