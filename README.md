# COBOL-Cheat-Sheet

- [Install COBOL Compiler](#install-cobol-compiler)
- [VS Code Extensions](#vs-code-extensions)
- [Create COBOL File](#create-cobol-file)

## Install COBOL Compiler

### update/upgrade
```bash
sudo apt-get update
sudo apt-get upgrade
```
### Compiler download

```
sudo apt install gnucobol
```

### verify COBOL installation

```
cobc --version
```

## VS Code Extensions

```
IBM Z Open Editor
```

```
Zowe Explorer
```

## Create COBOL File

### COBOL file extensions: 

- .cob
- .cbl
- .cobol

### Compile/Run COBOL file

Compile COBOL file

```
cobc -x <filename>
```

Run compiled COBOL file

```
./<filename>
```

