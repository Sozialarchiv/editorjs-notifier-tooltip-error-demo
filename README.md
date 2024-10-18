# editorjs-notifier-tooltip-error-demo

Pull request: https://github.com/codex-team/editor.js/pull/2842

## Run

```
yarn install
yarn build
```

## Error

```php
 tsc && vite build
node_modules/@editorjs/editorjs/types/api/notifier.d.ts:1:78 - error TS2307: Cannot find module 'codex-notifier' or its corresponding type declarations.

1 import {ConfirmNotifierOptions, NotifierOptions, PromptNotifierOptions} from 'codex-notifier';
                                                                               ~~~~~~~~~~~~~~~~

node_modules/@editorjs/editorjs/types/api/tooltip.d.ts:4:46 - error TS2307: Cannot find module 'codex-tooltip' or its corresponding type declarations.

4 import {TooltipContent, TooltipOptions} from 'codex-tooltip';
                                               ~~~~~~~~~~~~~~~


Found 2 errors in 2 files.

Errors  Files
     1  node_modules/@editorjs/editorjs/types/api/notifier.d.ts:1
     1  node_modules/@editorjs/editorjs/types/api/tooltip.d.ts:4
error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
