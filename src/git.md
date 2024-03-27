# git

## Commit Messages

- `feature` – a new feature is introduced with the changes
- `fix` – a bug fix has occurred
- `refactor` – refactored code that neither fixes a bug nor adds a feature
- `docs` – updates to documentation such as a the README or other markdown files
- `test` – including new or correcting previous tests
- `revert` – reverts a previous commit
- `cleanup`- Regular code maintenance.

Options:

- `ci` – continuous integration related
- `build` – changes that affect the build system or external dependencies
- `style` – changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
- `perf` – performance improvements
- `deps` - dependency
- `git`  - git specific files

Example:

- fix(ci) : fix gitlab build job for window
- clenaup(ci) : gitlab build job for window


## Usual Commands

### Big repo staff

```sh
git clone --filter=blob:none https://github.com/torvalds/linux.git
git clone --filter=tree:0 https://github.com/torvalds/linux.git
```
