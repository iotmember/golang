# golang
Learn golang

#Use GIT
http://labs.septeni-technology.jp/none/su-dung-git-trong-ubuntu/

#Good Document for Go lang
https://golang.org/doc/code.html
https://gobyexample.com/
http://www.golang-book.com

#Start a project
1. Create a workspace
$ mkdir $HOME/work
$ export GOPATH=$HOME/work
$ export PATH=$PATH:$GOPATH/bin

$ mkdir $GOPATH/src/github.com/iotviet_member/hello

2. Code
Next, create a file named hello.go inside that directory, containing the following Go code. 
package main

import "fmt"

func main() {
	fmt.Printf("Hello, world.\n")
}

3. Install
$ go install github.com/iotviet_member/hello

4. Run program
$ $GOPATH/bin/hello
Hello, world.

$ hello
Hello, world.

