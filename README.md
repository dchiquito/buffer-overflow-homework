# buffer-overflow-homework
Just a quick homework problem solution

# Setup
As described in the setup, you need to disable Address Space Randomization:
```
sudo sysctl -w kernel.randomize_va_space=0
```

I already use zsh, but if you don't, you need to for this lab.

The files given for the lab are included in `Labsetup`.

# Part 1
I ran `make` inside `Labsetup/shelllcode`. It created two files, `a32.out` and `a64.out`.
In order to compile the 32 bit executable, I had to run `sudo apt-get install gcc-multilib g++-multilib`.

Running either executable resulted in a shell, as expected.
`whoami` returns my user.
