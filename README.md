This is an example of a 3rd party package (library) for [Onyx](https://onyxlang.io/).

Onyx package management does **not** require a centralized registry like `npm` for Javascript or `Gem` for Ruby.
A repository for a package only needs to be published in a Git repository, such as GitHub, and be accessible to the users of the package.

Official docs: https://onyxlang.io/docs/packages

### Steps to try publishing a package yourself to learn

1. Prerequisites: `onyx`. See https://onyxlang.io/docs/install
2. `git clone` this repository to your github account.
3. Make any changes you like under the `src` folder, and commit and push it.
4. Change the metadata in `onyx-pkg.kdl` to your own accordingly.
5. Then run `onyx pkg publish`

The `onyx pkg publish` will increment the version number in `onyx-pkg.kdl` appropriately, create a tag with that version number, and push it automatically.

I feel very comfortable with this package management developer experience in Onyx.
