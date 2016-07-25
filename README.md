# Debug a Script Lab

## Objectives

1. Use Node built-in debugger by putting statements into a given script to find
   a problem by using `debugger`
1. Launch debugger
2. Fix the script

## Introduction

You've been hired by a major national bank to fix some of their account creation
code. Some bugs have crept into the code (as bugs are wont to do).
Your job is to fix the issues and make the code functional again.

In this lab, you'll debug a Node script which has some issues.

## Instructions

1. Open `account.js` then launch it from the command line with `node account`.
2. Find the issues
3. Put some `debugger` statements in `account.js`
4. Launch in debug mode with `node debug account`
5. Track the issues
6. Fix the file. (Hint: there are 3 issues to fix.)
7. Run test with `npm test`

**Note**: In order to debug the exported function in `account.js`, you'll need
to call the function somewhere in that file. Simply add a call to `account()` at
the bottom of the file and your break statements should work. Remove this call
before running the tests.

The fixed script should output the following:

```
Account before opening:  { balance: 0, name: 'Azat Mardan', checking: '1' }
New balance after signup bonus is 250
Account after opening:  { balance: 1250,
  name: 'Azat Mardan',
  checking: '1',
  type: 'checking' }
```

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/node-debugger-lab' title='node-debugger-lab'>node-debugger-lab</a> on Learn.co and start learning to code for free.</p>
