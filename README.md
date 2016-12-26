# dotvim

This vim config is inspired by this blog post: 
https://realpython.com/blog/python/vim-and-python-a-match-made-in-heaven/

## Troubleshooting

How to resolve broken powerline font issue?
- On Mac OSX, you need to install powerline fonts to avoid broken symbols: https://github.com/powerline/fonts
- Install iTerm2: *brew install Caskroom/cask/iterm2*
- And then set the terminal profile fonts: https://gist.github.com/wm/4750511

Error message at vim startup: "YouCompleteme unavailable : no module named future" issue?
- This means that the python-future submodule was not checked out. Go to YCM folder and run the following command: *git submodule update --init --recursive*
