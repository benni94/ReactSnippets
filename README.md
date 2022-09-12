# Depending on your plaform, your user snippets file is located here:

* Windows %APPDATA%\Code\User\snippets\(language).json
* Mac $HOME/Library/Application Support/Code/User/snippets/(language).json
* Linux $HOME/.config/Code/User/snippets/(language).json
 
 #### To create a new one:
 1. in Vsc search for '>User Snippets'
 2. choose 'New Global Snippets file...'
 3. remove the uncommitted lines in the { } and place a code like this example:

> {
  "Print to console": { &larr; the object identifier
    "prefix": "csl",    &larr; the prefix to use it in vsc
    "body": [           &larr; body element which gets written in vsc
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"console.log(`'${1:desc}',${2:val}`);"
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;],
    "description": "Logs something to the console" &larr; the description for the preview
&nbsp;&nbsp;&nbsp;}
}

the $ sign with the number afterwards defines the stepps which could be toggled with the tab key

now it can be called like this in vsc: 

<img src="https://res.cloudinary.com/practicaldev/image/fetch/s--miNnf4Qs--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e9ee6i8fh1u5nnfx4v2c.gif"  />

