Intro too Haskell
=================

### Setup:

1. [Install Haskell on your system](https://www.haskell.org/downloads)
2. Make sure you have cabal and ghc installed: `which cabal` `which ghc`
3. Clone this repo: `git clone https://github.com/ifo/intro-too-haskell.git`
4. Enter the repo directory: `cd haskell-command`
5. Create a cabal sandbox: `cabal sandbox init`
6. Create a cabal project: `cabal init --is-executable -n --source-dir=src --main-is=command.hs`
7. Start editing command.hs in the src directory: `vim|emacs|subl src/command.hs`
