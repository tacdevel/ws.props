[![License][Badges.License]][Links.License]

# TACDevel Common MSBuild Properties

This repository contains common workspace properties ([`ws.props`][Links.WSPropsFile]), which
contains reusable MSBuild properties that help keep our repositories organized.

## Using `ws.props`

1. Create a folder in the root of your repository named `.ws/`.
2. [Download the current `ws.props` file], and copy it to the `.ws/` folder you created.
3. Create a file named `ws.config.props` in the root of your repository.
4. Override/Configure whatever properties from `ws.props` that suit your fancy.
5. Import the `ws.props` file into your project. (Don\'t worry, your `ws.config.props` are automatically imported.)

You can alternatively add this repository into a submodule located at `.ws/` in the root directory of your project,
then follow steps 3 through 5 listed above.

<!-- Badges -->
[Badges.License]: https://badgen.net/badge/license/MIT/blue

<!-- Links -->
[Links.License]: https://github.com/tacdevel/ws.props/blob/master/LICENSE.md
[Links.WSPropsFile]: https://github.com/tacdevel/ws.props/blob/master/ws.props