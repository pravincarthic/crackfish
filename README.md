# Crackfish
Custom modded stockfish trained almost exclusively on meme games, designed as a small fun hobby project.
Made on Kaggle, not made to be serious, just enjoy the binaries.
## Running method
Follow these given steps to make sure prerequisites are there if you want to train (for Linux only):
```
sudo apt-get update
sudo apt-get -y install git python3-pip gcc-10 g++-10 zlib1g zlib1g-dev ninja-build
pip3 install meson --break-system-packages
pip -q install python-chess # Use only if you are using this package specifically
```

Current version is available as the binary, run:
```
chmod +rwx crackfish1924
```
then
```
./crackfish1924 # Use for a dry run, if you want to actually play, use any environment where you can import the engine
```
