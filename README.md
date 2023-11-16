# Wisebash

Some bash scripts for making one developer's life a little bit wiser through fortune :) feel free to contribute.

## Install

### Dependencies

Install the following dependencies:

```
fortune
cowsay
lolcat
```

### Install scripts

After installing dependencies, do the following sequence of commands to install the scripts from this repo.

1. Make the scripts executable in your computer by running:

```
chmod +x wisegit
chmod +x wiseclear
```

2. Copy files to a directory that is included in you PATH. In this example, we are going to use `/usr/local/bin`:

```
cp wisegit wiseclear /usr/local/bin
```

That's it! Next time you open terminal, you can use the scripts by calling `wiseclear` anywhere, and `wisegit` inside a folder that contains a git repository.
