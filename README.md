# greasygit (fork)
greasygit helps migrate a script published on Greasy Fork to Git with history (commits) kept intact.

This is a quick fork of the original with the minimal changes to make it work.

## Requirements

- requests (`pip install requests` or `pip install -r requirements.txt`)

## Run
```sh
python -V # Python version >= 3.6 should work well.
cd workspace # or other direcotry. greasygit will create a project directory there automatically.

curl -LO https://raw.githubusercontent.com/Gowee/greasygit/master/greasygit.py
chmod +x greasygit.py
./greasygit.py # Following the prompts to proceeed.

cd <REPO> && git log # Check the resulted commits.

git remote add <REMOTE> ... # Add a remote.
git push -u <REMOTE> <BRANCH>... # Push!
```

## Demo
Terminal recording:
https://asciinema.org/a/LQ72CJwCNyJ9k5XglOJhOdDjV
