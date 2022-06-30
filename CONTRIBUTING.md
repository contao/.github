# Contributing to Contao

The following is a set of guidelines for contributing to Contao and its
packages, which are hosted in the [Contao organization][1] on GitHub. These
are just guidelines, not rules, use your best judgement and feel free to
propose changes to this document in a pull request.

## Issues

 * Use the search function to see if a similar issue has already been
   submitted.
 * Describe the issue in detail and include all the steps to follow in order to
   reproduce the bug in the [online demo][2].
 * Include the version of Contao and PHP you are using.
 * Include screenshots if possible; they are immensely helpful.
 * If you are reporting a bug, please include any related error message you are
   seeing and also check the `var/logs/` directory for related log files.

## Pull requests

 * Follow the Contao coding standards.
 * For new features, create your pull request against the `5.x` branch.
 * For bug fixes, create your pull request against the lowest affected branch
   that is actively supported, e.g. `4.9` if the bug is in Contao 4.9 or `4.12`
   if the bug is only in Contao 4.12 or greater.
 * Include screenshots in your pull request whenever possible.
 * If you want to add a new feature, we recommend that you discuss your ideas
   with us before your start writing code; either on GitHub or in one of our
   [monthly calls][3].

## Git commit messages

 * Use the present tense ("Add feature" not "Added feature").
 * Use the imperative mood ("Move cursor to …" not "Moves cursor to …").
 * Reference issues and pull requests liberally.

## Release Plan

* Each new minor version is developed for about six months. During this period new 
  features may be added via pull requests to the [mono repo][4]. 
* You can see, when a new release is developed and published on the 
  [Contao project website][5]. This are approximations ;-)
* In order for your pull request to be considered for the upcoming release, be aware 
  that your pull requests must be „ready to merge“ two weeks before the end of the 
  development period:
   * The PR must be feature-complete
   * Each feature is covered with unit tests
   * All lights in the CI pipeline are green

[1]: https://github.com/contao
[2]: https://demo.contao.org/contao
[3]: https://contao.org/en/mumble-calls.html
[4]: https://github.com/contao/contao
[5]: https://contao.org/en/release-plan.html
