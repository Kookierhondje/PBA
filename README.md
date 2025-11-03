Add the following to your .bashrc or a script you wanna use the aliases in. 
Naturally you need to provide the location of the file, should you not put it in your user directory like this example expects.
```if [ -f ~/.bash_python_aliases ]; then
    source ~/.bash_python_aliases
fi
