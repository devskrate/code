---
layout: post
title: GO
nav_order: 8
toc: true
---

# Introduction to Go

### About the Tutorial
```go
package main
import "fmt"
// this is a comment
func main() {
 fmt.Println("Hello World")
}
```

<aside class="sidebar__right sticky">
    <nav class="toc">
      <header>
        <h4 class="nav__title"><!-- <i class="fas fa-cog"></i> -->
         Table of Contents</h4>
      </header>

  * Do not remove this line (it will not be displayed)
{:toc}

  </nav>
</aside>

<p><button class="btn js-toggle-dark-mode">Preview dark color scheme</button></p>
<script type="text/javascript" src="https://pmarsceill.github.io/just-the-docs/assets/js/dark-mode-preview.js"></script>


### What is Go?

**Go** is a statically typed], compiled programming language at Google by Robert Griesemer, Rob Pike, and Ken Thompson. Go is syntactically similar to C, but with memory safety, garbage collection, structural typing, and CSP-style concurrency. The language is often referred to as "Golang" because of its domain name, `golang.org`, but the proper name is Go. 

So, okay... let's go on to a more of realistic view ie., where `golang` is used?

Go can be used in

+ **OS Kernel and Firmware Development**
+ **Desktop UI Development**
+ **Web Frontend**
+ **Mobile App Development**

and many other industry level developments. Also do have a note that, **Go** is still in initial stages and is capable of doing miracles, once it's fully developed in a Big Picture.



> Go language is the C for the twenty-first century when it comes to syntax.



### Why Go?

The developers are always in search of an easier, more sophisticated and more project-friendly language that meet their needs. [GoLang](https://golang.org/) came as such as astounding new programming language with a full pack of solutions. Ever since it arrived, GoLang took the entire programming world by surprise.

#### The Core Capability of GoLang:

* Fast-paving compilation and execution
* Do away with the need of working with different subsets of languages for one project.
* A boost to code readability and documentation
* Offering a thoroughly consistent language
* Facilitating easy versioning of the program



This is just the first phase of GoLang and there are many other capabilities like  

* Allowing developing with multiple languages
* Allowing easier maintenance of dependencies
* Simplicity of Go
  * No Generics
  * Single Executable
  * No Dynamic Libraries
* Inbuilt Framework for Testing and Profiling

GoLang came as a massive value addition to the programming of complex applications underlying performance-savvy hardware systems and large scalable enterprise software systems. No wonder, within a few years it received such a vast following from developers around the globe.





![image-20200521174531344](.\go-layers.jpg)





### Getting up and running in Go

You have a few options for getting into Go, depending on your level of commitment.

 The easiest way to get started with Go is through a tour at [http://tour.golang.org](http://tour.golang.org), which walks you through using some of its main features. What separates the Go tour from this tutorials is in how the examples work. You can execute the examples right in your browser. If you want to change them and execute your changes, you can do that as well.

 If you want to try executing simple Go applications, you can do that through the Go Playground at [https://play.golang.org](https://play.golang.org). The Go Playground is what enables the tour examples to be executable. Here you can test code and share a link to it. The examples in this tutorial that represent a program can be executed in the Playground. 

**If you are more committed to learn `golang`, we recommend to install Go on your local machine to work seamlessly.**



### Installing Go

Installing Go is a fairly straightforward process.

+ Go to the official **Go Programming Language** [Downloads Page](https://golang.org/dl/).
+ You can take a look at all the available platforms that Go is working on.
+   Then download GoLang for the platform you're having ie., Windows, MacOS and Linux.
+ After downloading, you can install Go similar to any other software you install on your computer.

#### System Requirements

| **Operating System**              | **Architecture**                           | **Notes**                                                    |
| --------------------------------- | ------------------------------------------ | ------------------------------------------------------------ |
| FreeBSD 10.3 or later             | amd64, 386                                 | Debian GNU/kFreeBSD not supported                            |
| Linux 2.6.23 or later with glibc  | amd64, 386, arm, arm64,<br/>s390x, ppc64le | CentOS/RHEL 5.x not supported.<br />Install from source for other libc. |
| macOS 10.11 or later              | amd64                                      | use the clang or gcc that comes with Xcode for `cgo` support |
| Windows 7, Server 2008R2 or later | amd64, 386                                 | use MinGW (`386`) or MinGW-W64 (`amd64`) gcc.<br/>No need for cygwin or msys. |

**We recommend to go with the latest version of Go Programming Language.**

Using the latest version makes your learning more flawless without any bugs and errors in the language.

#### Checking GoLang version

To know the version of **Go** installed in your machine use thecommand `go version` in Command Prompt for Windows and Terminal for Linux and MacOS.

![Go Version](./go-version.jpg)



### Your First Program in Go

Traditionally the first program you write in any programming language is called a “Hello World” program – a program that simply outputs Hello World to your terminal. Let's write one using Go.

```go
package main
import "fmt"
// this is a comment
func main() {
 fmt.Println("Hello World")
}
```

Make sure your file is identical to what is shown here and save it as `main.go`.

By seeing the code above