sp - Symfony console commands Prompt

===

Interactive input assist tool for Symfony console command.

## Usage

### Execute command

```
sp
```

NOTICE: If you do not register commands you need to do it first.

### Register command

```
sp add -c /path/to/symfony-command

cd /path/to/command-dir
sp add -c command
```

### Change cache directory

default: `~/.sp`

```
sp setCacheDir -c ~/.symfony-command-cache
```

### Show version

```
sp version
```
