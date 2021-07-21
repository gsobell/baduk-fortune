```cow
        
                 ____________ 
                < Go is hard >
                 ------------ 
                        \   ^__^
                         \  (oo)\_______
                            (__)\       )\/\
                                ||----w |
                -Cho U, 9d      ||     ||

```
# baduk-fortune ○●
A collection of [baduk](https://en.wikipedia.org/wiki/Go_(game)) fortunes for the terminal


# Usage
Install [fortune](https://linux.die.net/man/6/fortune) or [fortune-mod](https://github.com/shlomif/fortune-mod)

`fortune` is a commnad line program that displays a quote or proverb when run. Sort of like a low-calorie fortune cookie.

```shell
# Debian/Ubuntu
$ sudo apt install fortune-mod

# Arch
$ sudo pacman -S fortune-mod

# Mac
$ brew install fortune
```
Save the list of fortunes and the corresponding `.dat` file to `/usr/share/fortune/`, either manually, or by running the following

```shell
curl -O baduk -O baduk.dat
sudo mv baduk baduk.dat /usr/share/fortune/
```
Open a terminal, and run 

`fortune baduk`

To receive a new fortune every time you log on, add the above to your shell config (i.e. `.bashrc` or `.zshrc`) 

# Q&A
Q: Why isn't it called go-fortune?

A: Because it [already exists](https://github.com/bmc/fortune-go), it's a fortune rewrite in GoLang.

Q: My favorite quote is missing. Can you add it?

A: Sure! Open an issue or pull request!

Q: Does it support GTP (Go Text Protocol)?

A: I'll get back to you on that. 


Fortunes sourced from:

[Sensei's "Great Quotes"](https://senseis.xmp.net/?GreatQuotes) - 
[Sensei's "Old Mottos"](https://senseis.xmp.net/?OldMottos) -
[Sensei's "Humour Q&A"](https://senseis.xmp.net/?HumourQandAs) - 
[Sensei's "Almost Proverbs"](https://senseis.xmp.net/?HumourAlmostProverbs) - 
[Kiseido Quotes](https://kiseido.com/yyy.htm) -
[Wikiquote Go](https://en.wikiquote.org/wiki/Go_(game)) 

***

List was scrubbed for uniformity, brevity, and duplicates.
Proverbs that needed further context were selectively excluded.
I tried not to include any "rude" or "crude" items from the above lists, please let me know if you find one.
