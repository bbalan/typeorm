# TypeORM fork

This fork has been hacked to replace `react-native-sqlite-storage` with `react-native-sqlite-2`.

## Upgrading

The fork was originally based on `typeorm@0.2.31`. When it's time to upgrade, do this:
```
git checkout master
git fetch upstream
git checkout rn-sqlite-2
git rebase -i master
```
