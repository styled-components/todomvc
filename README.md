# React TodoMVC example with styled-components

This is the [Speedometer 2.0 React TodoMVC example](https://github.com/WebKit/webkit/tree/master/Websites/browserbench.org/Speedometer2.0/resources/todomvc/architecture-examples/react) rebuilt with styled-components.

## Notes

I had to add the `babel-plugin-transpile-es2015-template-literals` because Uglify chokes on the tagged template literal syntax.

## Test locally

1. `npm install`
2. Run a local server from this directory. (You could use [`npm i -g http-server`](https://github.com/indexzero/http-server).)
3. Open the URL pointing to the local server in your web browser of choice.

## Build

1. `npm run build`
