# xcode-themes

Color themes for Xcode. This is a collection of XCode themes I've found elsewhere on GitHub and a few I've made too.


## Usage

To install a theme in XCode just copy a `.xccolortheme` to XCode's themes folder (`$HOME/Library/Developer/Xcode/UserData/FontAndColorThemes/` it may need to be created).

```bash
git clone https://github.com/ziqq/xcode-themes
cd xcode-themes
mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
cp *.xccolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
```

Restart Xcode after copying the themes, then select one under **Xcode →
Settings → Themes**.

## Themes

### CodePen

The CodePen Original palette adapted to Xcode's syntax roles, source editor,
debug console, documentation markup, selection, and diagnostic markers. This
variant uses SF Mono without coding ligatures.

### CodePen (Ligatures)

The same colors with `VictorMono-Regular` and `VictorMono-Italic`. Install
[Victor Mono](https://rubjo.github.io/victor-mono/) before selecting this
variant. Xcode gets coding ligatures from the selected font; an
`.xccolortheme` has no separate ligature switch.

Xcode color themes cannot recolor the navigator, toolbar, tabs, or other IDE
chrome. Those surfaces continue to follow the macOS and Xcode appearance.

### BigMountainStudio (Dark)
![BigMountainStudio](screenshots/BigMountainStudio.dark.png)

### BigMountainStudio (Light)
![BigMountainStudio](screenshots/BigMountainStudio.light.png)

### GitHub (Dark)
![GitHub (Dark)](screenshots/GitHub.dark.png)

### GitHub (Light)
![GitHub (Light)](screenshots/GitHub.light.png)

### GruvBox
![GruvBox](screenshots/GruvBox.png)

### Twilight
![Twilight](screenshots/Twilight.png)

### Ziqq
![Ziqq](screenshots/Ziqq.png)
