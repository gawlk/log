# log

![preview](log.png)

## Description

`log` is a very simple library that I made because I realized that I always needed something like logs to keep track of what is going on in my scripts.

Bonus: It has colors !

## How to use ? 

It's very easy:
1. Download and put the script in your path
2. Add `. log` at the top of your scripts
3. That's it, you can now use the available functions !

## Manual

Example: `log.info "test" "test"`

Available getters:
- `log.is_quiet`: Return `true` if `log.info` is hidden
- `log.is_loud`: Return `true` if `log.info` is not hidden
- `log.is_dev`: Return `true` if `log.dev` is hidden
- `log.is_casual`: Return `true` if `log.dev` is not hidden

Available printers:
- `log.info` : Display an information
- `log.debug`: Used for debugging (default: hidden)
- `log.warning`: Used for warnings
- `log.error`: Display an error and quit
- `log.quit`: Display an information and quit

Available setters:
- `log.quiet`: Hide `log.info`
- `log.loud`: Show `log.info`
- `log.dev`: Show `log.debug`
- `log.casual`: Hide `log.debug`
