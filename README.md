# VS Code Settings
## Web Stack
Thank you for using the iTEAM Consulting VS Code workspace settings for web development. Packaged with these settings are a set of extension recommendations.  We suggest you follow these recommendations for the best development experience.

## Usage
### Adding to a Project
Navigate a prompt to your project directory and run the following command:
```
git submodule add https://github.com/iteam-consulting/vsc-settings-web.git .vscode
```
This settings package uses [Fira Code](https://github.com/tonsky/FiraCode) with ligatures enabled. If you do not install the font, it will default to a system font and looks terrible. We suggest you either install the font, or override the workspace setting in your environment.

*Note: make sure you are not ignoring the `.vscode` directory*

### Cloning a Repo With This Submodule
Run the following commands:
```
git submodule init
git submodule update
```

### Debugging in Chrome (React)
1. Install the recommended chrome debugger in VS Code.
2. Run the application
```
npm start
```
3. Start a debugging session (By hitting <kbd>F5</kbd> or by starting in the debug sidebar).
4. Set your breakpoint.
5. Debug.

Note: You must use the window that the debug session started. Do not close it, unless you wish to end your debug session.

## Authors
iTEAM Consulting Software Development Team

## Questions
Contact [software@iteamnm.com](mailto:software@iteamnm.com) for questions.
