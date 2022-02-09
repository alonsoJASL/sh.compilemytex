# sh.compilemytex
Compile your LaTeX files with pdf LaTeX with ease.

## Quick guide
Place this file in the same directory as your LaTeX project. 

**Add permissions to the file** by typing: 
```bash
chmod 755 ./rerunpdf
```

Add a symbolic link to the `/usr/local/bin` folder (you need to have admin permissions):
```bash
sudo ln -s $(pwd)/rerunpdf.sh /usr/local/bin/compile-tex
```

You can now use the script for your LaTeX code: 

**Get help**
```bash
compile-tex -h
```

**Run your code** where the main `tex` file is called `rootfile.tex`. 
```bash
compile-tex rootfile
```
