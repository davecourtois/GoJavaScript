# GoJavaScript

GoJavaScript give you full access to Javascript from inside your Go application. Not only you can run JavaScript code from Go but you can access Go object or function from inside your JavaScript code. With GoJavaScript, you combine the flexibility of JavaScript and the speed of Go!-)</br>
Duktape is the JavaScript engine used by GoJavaScript. Tank's to it simplicity, no external library is require and it run almost everywhere. In order to get more stability, GoJavaScript was split in tow part, the server side and the client side. Both part communicate together via a TCP socket. From the client perspective, GoJavaScript is used like a regular Go package. 

### Installing

To get the package simply run

```
go get github.com/davecourtois/GoJavaScript
```
Now we need to build and install the server side executable that contain the interpreter.

```
go build github.com/davecourtois/GoJavaScript/GoJavaScriptServer

go install github.com/davecourtois/GoJavaScript/GoJavaScriptServer
```
Also be sure to have the GOROOT/bin directory in your path.

## Getting Started

I invite you to read GoJavaScriptTest to see how to use the library. Each test are self contained and well documented. I'm about to wrote a blog on how to use GoJavaScript in your application I will publish the link here.

## Running the tests

To run the test simply execute,

```
go test github.com/davecourtois/GoJavaScript/GoJavaScriptTest
```

## Authors

Dave Courtois

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thank to Sami Vaarala for it work with Duktape.
* The first inspiration came from Robert Krimen and it work with Otto.

