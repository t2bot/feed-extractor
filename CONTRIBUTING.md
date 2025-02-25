# Contributing to `@extractus/feed-extractor`

Glad to see you here.

Collaborations and pull requests are always welcomed, though larger proposals should be discussed first.

As an OSS, it's better to follow the Unix philosophy: "do one thing and do it well".


## What you can contribute?

We are planing to re-write this tool in TypeScript and make it Deno-first library.
If you are interested, please join our team.

Besides that, you can also:

- Test and report bugs
- Fix unresolved issues
- Improve performance
- Write better documentation
- Create examples or build demos
- Feedback on software design and APIs


## Third-party libraries

Please avoid using libaries other than those available in the standard library, unless necessary.

This library needs to be simple and flexible to run on multiple platforms such as Deno, Bun, or even browser.


## Coding convention

Please follow [standardjs](https://standardjs.com/) style guide.

Make sure your code lints before opening a pull request.


```bash
cd feed-extractor

# check coding convention issue
npm run lint

# auto fix coding convention issue
npm run lint:fix
```

*When you run `npm test`, the linting process will be triggered at first.*


## Testing

Be sure to run the unit test suite before opening a pull request. An example test run is shown below.

```bash
cd feed-extractor
npm test
```

![feed-extractor unit test](https://i.imgur.com/2b5xt6S.png)

If test coverage decreased, please check test scripts and try to improve this number.


## Documentation

If you've changed APIs, please update README and [the examples](examples).


## Clean commit histories

When you open a pull request, please ensure the commit history is clean.
Squash the commits into logical blocks, perhaps a single commit if that makes sense.

What you want to avoid is commits such as "WIP" and "fix test" in the history.
This is so we keep history on master clean and straightforward.

For people new to git, please refer the following guides:

- [Writing good commit messages](https://github.com/erlang/otp/wiki/writing-good-commit-messages)
- [Commit Message Guidelines](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53)


## License

By contributing to `@extractus/feed-extractor`, you agree that your contributions will be licensed under its [MIT license](LICENSE).

---
