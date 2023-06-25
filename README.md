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

### Installation
Install [fortune](https://linux.die.net/man/6/fortune) or [fortune-mod](https://github.com/shlomif/fortune-mod) (or even [misfortune](https://github.com/ncfavier/misfortune)).

`fortune` is a command line program that displays a quote or proverb when run. It is available on most operating systems:

```shell
# Arch
sudo pacman -S fortune-mod

# Debian/Ubuntu (WSL)
sudo apt install fortune-mod

# openBSD
doas pkg_add fortune

# nix-shell
nix-shell -p fortune

# Mac
brew install fortune
```
Save the list of fortunes and the corresponding `.dat` file to `/usr/share/fortune/` by running the following:

```shell
curl -LO https://github.com/gsobell/baduk-fortune/raw/shodan-branch/baduk
curl -LO https://github.com/gsobell/baduk-fortune/raw/shodan-branch/baduk.dat
sudo mv baduk baduk.dat /usr/share/fortune
```

To install on Arch-based distros, use the [PKGBUILD](https://github.com/gsobell/baduk-fortune/blob/shodan-branch/PKGBUILD):

```sh
curl -O https://raw.githubusercontent.com/gsobell/baduk-fortune/shodan-branch/PKGBUILD
makepkg -i
```

To recieve a fortune, open a terminal, and run:

`fortune baduk`

For a new fortune every time you log on, add the above to your shell config (i.e. `.bashrc` or `.zshrc`)
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
Any "rude" or "crude" items from the above lists were excluded, please open an issue if you find one.
