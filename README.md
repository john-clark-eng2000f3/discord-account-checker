# discord-account-checker

I manage a few Discord alt accounts and got tired of logging into each one
to check if the token was still good. This script hits a few Discord REST
endpoints and prints a quick health summary.

## install

pip install -r requirements.txt

## usage

python checker.py --tokens YOUR_TOKEN

python checker.py --tokens-file ~/.discord_tokens.txt

Tokens are read one per line, blank lines and lines starting with # are skipped.

<!-- refreshed: 2026-10-05 -->
