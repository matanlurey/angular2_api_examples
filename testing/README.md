An example of using the new `NgTestBed` API.

![demo3](https://cloud.githubusercontent.com/assets/168174/19536743/156845e4-9602-11e6-9f39-b682176b370b.gif)

To run, simply use `pub`:

```bash
$ pub serve
```

In Chrome or Dartium, open up `http://localhost:8080`

You'll see the Angular Dart github issues displayed in a table like you see above.

To run the automated tests, open up:

1. `http://localhost:8081/issue_body_test.dart`
2. `http://localhost:8081/issue_list_test.dart`

The first test is a simple "do we parse the markdown", test.

The second test is an e2e-style test that uses [pageloader][pageloader].

[pageloader]: https://github.com/google/pageloader
