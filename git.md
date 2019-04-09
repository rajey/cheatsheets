# Git cheatsheets

## git csv export

`git log --since='<period>' --date=local --pretty=format:'%h,%an,%ad,%s' --all > /<filename>.csv`

- period: time when you want logs retrieved to current
- filename: name of csv file to generate
- --all option allow you to get commits from all branches
