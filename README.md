# spring-react-boilerplate

An example application that uses a Spring Java backend with a React
frontend.

## Another Boilerplate?

Yes, but with Java. It's inspired by the
[spring-react-isomorphic](https://github.com/sdeleuze/spring-react-isomorphic)
project, but uses:

- [Webpack](https://github.com/webpack/webpack) to bundle all the JavaScript and dependencies
- Hot module reloading (HMR) of React components
- [Redux](https://github.com/rackt/redux) to manage state, both in the
  client and when rendering on the server.
- [react-router](https://github.com/rackt/react-router) for page routing,
  on client and server
- [redux-simple-router](https://github.com/jlongster/redux-simple-router)
  to sync redux and react-router

## Other Goodies

You also get:

- [Project Lombok](https://projectlombok.org/) to cut down the Java
  boilerplate
- [Jackson](https://github.com/FasterXML/jackson) to serialize model data
  before rendering on the server. For more information, see [this OpenJDK
  thread on the
  subject](http://mail.openjdk.java.net/pipermail/nashorn-dev/2013-September/002006.html)
