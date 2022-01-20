npm init -y

## Typescript with git commit message linter
npm i -D @types/node typescript git-commit-msg-linter

## Eslint config standard with typescript
npm i -D typescript@\* eslint@^7.12.1 eslint-plugin-promise@^5.0.0 eslint-plugin-import@^2.22.1 \
eslint-plugin-node@^11.1.0 @typescript-eslint/eslint-plugin@^4.0.1 eslint-config-standard-with-typescript@latest

## Husky for git hooks and lint staged
npm i -D husky lint-staged

## Jest for tests
npm i -D jest @types/jest ts-jest

## All commands together
npm i -D @types/node typescript git-commit-msg-linter typescript@\* eslint@^7.12.1 eslint-plugin-promise@^5.0.0 \eslint-plugin-import@^2.22.1 eslint-plugin-node@^11.1.0 @typescript-eslint/eslint-plugin@^4.0.1 \eslint-config-standard-with-typescript@latest husky lint-staged jest @types/jest ts-jest
