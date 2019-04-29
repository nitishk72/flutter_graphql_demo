# Flutter GraphQL Demo

A new Flutter application with GraphQL.

## Getting Started

This app is using [graphql-flutter](https://github.com/zino-app/graphql-flutter#readme) Dependency. I am using version 1.0.0 of this plugin.

Those who are on`flutter stable channel` will not able to use the version `1.0.0` of this plugin because it requires Dart Tool >= `2.2.0` && < `3.0.0` .On stable channel currently flutter is using Dart < `2.2.0` .

To solve this issue you need to move to the dev channel of flutter which is currently using Dart >= `2.2.0`.

### Let's check the Dart version of Flutter

```sh
$ flutter --version
Flutter 1.5.8 • channel dev • https://github.com/flutter/flutter.git
Framework • revision 0ba67226ee (4 days ago) • 2019-04-24 17:18:28 -0700
Engine • revision c63d1cf9c9
Tools • Dart 2.1.0 (build 2.3.0-dev.0.1 1f1592edce)
```

You can see that `Tools • Dart 2.1.0 (build 2.3.0-dev.0.1 1f1592edce)` version is 2.1.0 ( < 2.2.0 ). So you need to change the channel, Here is instruction for changing the channel.

### To change the Channel

```sh
$ flutter channel dev
Switching to flutter channel 'dev'...

$ flutter channel
Flutter channels:
  beta
* dev
  master
  stable
```

Now you can clone this app and run in your Computer.

If you found any difficulties while running this app then feel free to open the issue.

