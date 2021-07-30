# log

The `Logger` interface can be used instead to give the user choice over which logger they want use

This lib ships with a default implementation of the `Logger` interface

[SimpleLogger](https://github.com/DisgoOrg/log/blob/master/simple_logger.go) is a wrapped standard [Logger](https://pkg.go.dev/log) to fit the `Logger` interface

You can use your own implementation or a library like [logrus](https://github.com/sirupsen/logrus)
