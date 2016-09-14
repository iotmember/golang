#Learn golang

#Use GIT
http://thachpham.com/tools/cach-tao-repository-cho-git.html

#Good Document for Go lang
https://golang.org/doc/code.html
https://gobyexample.com/
http://www.golang-book.com

#Start a project
* Create a workspace

$ mkdir $HOME/work

$ export GOPATH=$HOME/work

$ export PATH=$PATH:$GOPATH/bin

$ mkdir $GOPATH/src/github.com/iotviet_member/hello


* Code

Next, create a file named hello.go inside that directory, containing the following Go code. 

package main

import "fmt"

func main() {
	fmt.Printf("Hello, world.\n")
}


* Install

$ go install github.com/iotvietmember/hello


* Run program

$ $GOPATH/bin/hello
Hello, world.

$ hello
Hello, world.

