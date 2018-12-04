# yarn-linked

List or remove yarn linked modules

    $ yarn-linked
    Linked modules in /home/user/projects/some-project/
        @prefix/package 0.1.1
            other-package 0.2.2
    
## Use globally

    yarn global add yarn-linked
    yarn-linked [path to project root, default cwd]

## Use in a project

    yarn add -D yarn-linked

**package.json:**

    "scripts": {
        "linked": "yarn-linked"
    }
