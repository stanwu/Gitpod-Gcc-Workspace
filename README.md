# gitpod_workspace
Gitpod Workspace

### build-tmux.sh

One step to build tmux

```
mkdir tmux
cd tmux
cp ../script/build-tmux.sh .
./builld-tmux.sh
```

### cp-deps


Copy ldd files of assigned command into target folder


```
cp-deps command [target_folder]
```

Example :

```
mkdir portable_mc
cp-deps mc portable_mc
```

