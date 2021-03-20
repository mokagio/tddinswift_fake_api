# TDD in Swift book – Fake API

This is the _fake_ API for the examples from the [Test-Driven Development in Swift with SwiftUI and Combine](https://tddinswift.com) book.

TDD is all about moving in small iterations, doing only the bare minimum to make your test pass and your code work.
In the same spirit, rather than spinning up a real API for the book, I decide to use static JSONs, hosted on GitHub so everyone can see them.

This is a great technique when building a real app too, by the way.
If you don't have a real API yet or are waiting for a new endpoint to be built, chuck up a static version of the response you expect on GitHub, S3, or any other system that can serve it to you over HTTP.
When the API is ready, you can simply switch the URL to the correct endpoint.
