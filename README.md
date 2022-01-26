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

## Usage
Install [fortune](https://linux.die.net/man/6/fortune) or [fortune-mod](https://github.com/shlomif/fortune-mod)

`fortune` is a command line program that displays a quote or proverb when run. It's sort of like a calorie-free fortune cookie.

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
curl -LO https://github.com/gsobell/baduk-fortune/raw/shodan-branch/baduk
curl -LO https://github.com/gsobell/baduk-fortune/raw/shodan-branch/baduk.dat
sudo mv baduk baduk.dat /usr/share/fortune
```
Open a terminal, and run 

`fortune baduk`

To receive a new fortune every time you log on, add the above to your shell config (i.e. `.bashrc` or `.zshrc`)  
For extra fun, use in conduction with `cowsay` or `cowfortune`!

## Q&A
Q: Why isn't it called go-fortune?  
A: Because it [already exists](https://github.com/bmc/fortune-go), it's a fortune rewrite in GoLang.

Q: My favorite quote is missing. Can you add it?  
A: Sure! Open a pull request! Since a new `.dat` file has to be generated each time, additions will be added in batches.


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
Any "rude" or "crude" items from the above lists were excluded, please open an issue if you find one.
