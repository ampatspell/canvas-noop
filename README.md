# canvas-noop

Workaround for `Module did not self-register: … canvas.node`

Replaces `canvas` with empty module for Ember app. Useful if `canvas` is used by other packages in workspace.

``` json
// an-ember-app/package.json
{
  "devDependencies": {
    "canvas": "ampatspell/canvas-noop"
  }
}
```
