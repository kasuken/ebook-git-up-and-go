# Install and Configure Git

1. Install Git: If you haven't already done so, download and install Git on your computer. You can find the download link at **[https://git-scm.com/](https://git-scm.com/)**.
2. Open the terminal: To configure Git, you'll need to use the terminal (or command prompt) on your computer. Open the terminal by searching for "Terminal" or "Command Prompt" in your operating system's search bar.
3. Configure your username: The first thing you'll need to do is configure your username in Git. This is the name that will be associated with the changes you make to your code. Type the following command in the terminal, replacing "Your Name" with your actual name:

```bash
git config --global user.name "Your Name"
```

1. Configure your email address: Next, you'll need to configure your email address in Git. This is the email address that will be associated with the changes you make to your code. Type the following command in the terminal, replacing "**[your.email@example.com](mailto:your.email@example.com)**" with your actual email address:

```bash
git config --global user.email "your.email@example.com"
```

1. Configure your default text editor: Git uses a text editor to display and edit text files, such as commit messages. You can configure your preferred text editor by typing the following command in the terminal, replacing "code" with the name of your preferred text editor:

```bash
git config --global core.editor code
```

1. Check your configuration: To check that your configuration has been set correctly, type the following command in the terminal:

```bash
git config --list
```

This will display a list of your Git configuration settings, including your name, email address, and text editor.
