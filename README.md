# Barebones ts-node script

## Usage

1. Clone this repo, then `cd barebones-ts-script`
2. Install dependencies: `yarn install`
3. Run the script: `bin/ts-node index.ts`
4. Run the tests: `bin/test`

## Motivation

It's surprisingly annoying to write an otherwise trivial script in Typescript. Every once in a while I want to quickly automate a small task. Out of habit I reach for Typescript, but each time I have to remind myself which dependencies for my typical, heftier projects are actually necessary for something that small.

This friction isn't huge—it's a question of just a few minutes—but it raises the activation energy needed to write a script to solve a little problem. Sometimes I just go with Javascript or Ruby instead, and sometimes I forgo writing the script at all.

The idea of barebones-ts is to provide the scaffolding for a trivial script so that I never have to think about that activation energy again. Hopefully you find it useful too!
