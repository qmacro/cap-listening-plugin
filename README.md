# CAP listening plugin

A super simple plugin that will touch (and therefore update the 'last modified' timestamp of) a file called `listening` in a CAP Node.js project's root directory.

For background, see [Controlling automatic HTTP requests in CAP Node.js design time loops](https://qmacro.org/blog/posts/2024/05/03/controlling-automatic-http-requests-in-cap-node.js-design-time-loops/). This project is essentially a cds-plugin powered version of the approach described in that blog post.

To use, just install as a dev dependency like this:

```shell
npm install \
    --save-dev \
    git+https://github.com/qmacro/cap-listening-plugin.git
```

or

```shell
npm install \
    --save-dev \
    github:qmacro/cap-listening-plugin
```
