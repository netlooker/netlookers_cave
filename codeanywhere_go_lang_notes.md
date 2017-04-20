# Preparing GO lang development stack on Codeanywhere

I've created a new container based on the blank Ubuntu 14.04. The GO container which is provided by the codeanywhere includes GO in version 1.6 which is not a recent one.

Shell dump for the operations that I've performed:
> ```
> sudo apt-get update
> sudo apt-get install software-properties-common
> sudo add-apt-repository ppa:gophers/archive
> sudo apt-get update
> sudo apt-get install nano
> 
> ```

Adding GO lang env. variables to the PATH variable

> nano ~/.profile

Append the following line at the end of the file :

> ```
> #Setting up GO lang env. variables                                                                                                                                                     
>export PATH=$PATH:/usr/lib/go-1.8/bin                                                                                                                                
>export GOPATH=$HOME/workspace 
> ```

Then logout/login on the terminal or run `source ~/.profile`

Create following directories in the `workspace` folder
> ```
> mkdir bin
> mkdir src
> ```

