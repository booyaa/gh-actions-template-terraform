# gh-actions-template-terraform

A starter template for terraform projects with GitHub Actions CI orientated workflow.

## Usage

- click on the `Use this template` button for this repo
- fill out the new project details
- git clone your new GitHub project
- cd to the project's directory
- add your terraform scripts to the project
- update this `README.md` to reflect your own project's awesomeness!

## Why

Continuous Integration (CI) is a way to mitigate potential problems arising from changes to code, dependencies or even version changes to the programming language that powers your awesome project. 

By continuously building and testing your code as changes arrive, you can have confidence that the code you merge won't break your project.`</soapbox>`

Setting up continuous integration pipeline for your projects can be tricky, but using GitHub Actions can make this incredibly easy and not require 3rd party services like [Travis CI][link_travis] or [Circle CI][link_circleci].

## What's in the box

- A CI workflow that runs the following terraform commands: `fmt`, `init`, `validate` and `plan`.

All of these actions are configurable, and documentation can be found [here][tfactions_docs]. Warning: the current docs still use HCL (v1) format, you will need to convert the examples to YAML (v2).
 
## What's not in the box

- A Continuous Delivery (CD) pipeline to run the `apply` command, this is very specific to each the type of terraform project and it's purposes i.e. cloud vendor.

## License

See [LICENSE](LICENSE).

## Copyright

Mark Sta Ana &copy; 2019 

<!-- linkies -->

[link_travis]: https://travis-ci.org
[link_circleci]: https://circleci.com
[tfactions_docs]: https://www.terraform.io/docs/github-actions/getting-started/index.html