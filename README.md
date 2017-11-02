# ember-concurrency-vscode-snippets

This extension contains helpful Ember snippets for [ember-concurrency](http://ember-concurrency.com/#/docs/introduction). This is a work-in-progress and additional imports will be included.

## Currently Supported Snippets
### Import

Input | Result
--- | ---
`imp e-c` | `import { task } from 'ember-concurrency';`
`imp e-c timeout` | `import { timeout } from 'ember-concurrency';`

### Tasks
Use tab to move through the task name, yield, and the last line.

Input | Result
--- | ---
`e-c task` | Generates a new ember-concurrency task.
`e-c task-restartable` | Generates a new ember-concurrency restartable task.
`e-c task-drop` | Generates a new ember-concurrency droppable task.
`e-c task-enqueue` | Generates a new ember-concurrency enqueued task.
`e-c task-keepLatest` | Generates a new ember-concurrency keepLatest task.