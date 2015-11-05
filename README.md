# snippts
Various snippets

// bash script to remove all code from javascript files including /*2989f2fb2a51a8628825606948606b5f*/../*2989f2fb2a51a8628825606948606b5f*/
$ find  . -type f -name '*.js' -print0 |  xargs -0 perl -i -0777pe  's|/\*2989f2fb2a51a8628825606948606b5f\*/.*?/\*2989f2fb2a51a8628825606948606b5f\*/||gs'
