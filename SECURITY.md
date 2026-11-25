# Security

## Reporting a problem
Found something unsafe in these files (for example an instruction that could make Claude leak or misuse an account)? Please use GitHub's **private vulnerability reporting** on this repository (Security tab, "Report a vulnerability"), or message [@asmosautoflow](https://www.threads.com/@asmosautoflow) on Threads. Do **not** post tokens, keys, passwords or screenshots that show them in an issue or in a public Threads post.

## What these files are
Plain text instructions that a person pastes into Claude. They contain **no code that runs by itself and no secrets**. Because Claude follows them, a changed copy could mislead it: get the files only from this repository and compare with `SHA256SUMS.txt` if in doubt.

## What the files never do
- They never ask for a password, token, API key, cookie or login code, and tell Claude to refuse one if it is pasted.
- They never tell Claude to log in for you, to automate Threads in a browser, or to post anything you did not ask for.

## The Zernio edition
Posts go through Zernio's own connector. Zernio, not this repository, holds the connection to your Threads account. Read Zernio's terms and privacy policy before using it.

## The Full edition
It sets up your own copy of an open-source connector (`peightproduction/threads-studio`) in your own accounts. Keep your Meta app secret and the passwords you create only in your own hosting settings, never in chat.
