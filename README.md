## GitHub Dark (Unofficial) Port

![GitHub Dark on Graviton2](https://i.ibb.co/GTcmTzw/Screen-Shot-2020-12-10-at-12-52-05-AM.png)

This theme is an unffocial port of the [GitHub Dark](https://github.com/StylishThemes/GitHub-Dark-Syntax-Themes) theme (that is the only link I can find right now - it seems that I am the first person to recreate this theme!).
Due to the differences between how GitHub and Graviton check and tokenize code for highlighting there will be small differences, but I have tried to keep this theme as accurate as possible

## 🕹 Developing
This theme has been tested in Graviton v2.1

## 💻 Installing
As of the time of writing (early December, 2020), there are some issues with where the default release of graviton2 looks for its plugin files on macOS. To fix this, open up the advanced settings JSON file, find the `appConfigPath` key, and change it's value to `/Users/<yourusername>/graviton2`. Now create a folder in your home directory called `graviton2`, as well as a folder inside `graviton2` called `plugins`. 

Open a new terminal and move to the `plugins` directory you just created. Now run 
```shell
git clone https://github.com/gaetgu/githubdark-graviton.git
```
If everything worked correctly, the **GitHub Dark** theme should be available in settings once graviton is restarted.

## ➕ Contribution
If you have any suggestions or improvements, please create an issue or a discussion (they're new, too!).
