# Cheats
Cheatsheets for [navi](https://github.com/denisidoro/navi).

## Cloning Cheats

```
git clone "git@github.com:mmmucky/cheats.git" "$(navi info cheats-path)/mmmucky__cheats"
```

## Updating Cheats

```
for dir in "$(navi info cheats-path)"/*__*; do
  cd "$dir" && git pull
done
```

## Alias so navi doesn't run commands by default

```
alias navi='navi --print'
```
