# Utils

[![](https://img.shields.io/github/license/cedoor/utils.svg?style=flat-square)](https://github.com/cedoor/utils/blob/dev/LICENSE)
[![](https://img.shields.io/david/cedoor/utils.svg?style=flat-square)](https://david-dm.org/cedoor/utils)
[![](https://img.shields.io/david/dev/cedoor/utils.svg?style=flat-square)](https://david-dm.org/cedoor/utils?type=dev)

Some JavaScript utils.

## Installing

### npm

You can install utils package with npm:

    npm install @cedoor/utils --save
    
### CDN

You can also load it using a \<script> using the unpkg CDN:
    
    <script src="https://unpkg.com/@cedoor/utils"></script>

## Development

For a faster and more efficient development, some rules are used in the commits, in the branches and in the ECMAScript 2015 syntax.

### # commits

* Use this commit message format (angular style):  

    `[<type>]: <subject>`
    `<BLANK LINE>`
    `<body>`

    where `type` must be one of the following:

    - feat: A new feature
    - fix: A bug fix
    - docs: Documentation only changes
    - style: Changes that do not affect the meaning of the code
    - refactor: A code change that neither fixes a bug nor adds a feature
    - test: Adding missing or correcting existing tests
    - chore: Changes to the build process or auxiliary tools and libraries such as documentation generation
    - update: Update of the library version or of the dependencies

and `body` must be should include the motivation for the change and contrast this with previous behavior (do not add body if the commit is trivial). 

* Use the imperative, present tense: "change" not "changed" nor "changes".
* Don't capitalize first letter.
* No dot (.) at the end.

### # branches

* There is a master branch, used only for release.
* There is a dev branch, used to merge all sub dev branch.
* Avoid long descriptive names for long-lived branches.
* No CamelCase.
* Use grouping tokens (words) at the beginning of your branch names (in a similar way to the `type` of commit).
* Define and use short lead tokens to differentiate branches in a way that is meaningful to your workflow.
* Use slashes to separate parts of your branch names.
* Remove branch after merge if it is not important.

Examples:
    
    git branch -b doc/README
    git branch -b test/one-function
    git branch -b feat/side-bar
    git branch -b style/header

### # es2015

* Use `let` and `const`, not `var`.
* Use Arrow Functions in place of function expressions when possible.
* Use Arrow Functions whenever you need to preserve the lexical value of this.

## License
* See [LICENSE](https://github.com/cedoor/utils/blob/master/LICENSE) file.

## Contacts
#### Developer
* e-mail : me@cedoor.dev
* github : [@cedoor](https://github.com/cedoor)
* website : https://cedoor.dev
