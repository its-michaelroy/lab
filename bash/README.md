## Command Substitution
$ bash
today=$(date +%Y-%m-%d)
echo "Today is $today"

Always use $() - it's easier to read and can be nested.

