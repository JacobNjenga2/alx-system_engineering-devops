# 0x03. Shell, init files, variables and expansions

This project contains various shell scripts that demonstrate shell variables, expansions, and aliases.

## Scripts

### 0-alias
Creates an alias where `ls` becomes `rm *`. This script demonstrates how to create aliases in bash.

**Usage:**
```bash
source ./0-alias
```

**Note:** This is a dangerous alias that will delete all files in the current directory when `ls` is used. To use the original `ls` command after creating this alias, use `\ls`. 