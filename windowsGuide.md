### Setting up Git in Windows

#### Step 1: Install Git for Windows

Download the latest Git for Windows installer from the [official Git website](https://git-scm.com/download/win), then run the downloaded file.

Follow the installer prompts. The default options work for most people. When asked how Git should be used from the command line, choose **Git from the command line and also from 3rd-party software** so you can run Git in PowerShell, Command Prompt, and other tools.

<div markdown="1">

#### Alternative: Install with winget

If you have [Windows Package Manager](https://learn.microsoft.com/windows/package-manager/winget/) installed, open PowerShell or Windows Terminal and run:

```powershell
winget install --id Git.Git -e --source winget
```

</div>

#### Step 2: Open a new terminal

After installation, close any open terminal windows and open a new one. This makes sure the terminal picks up Git's updated `PATH`.

#### Step 3: Verify Git version

Run this command in PowerShell, Command Prompt, or Git Bash:

```powershell
git --version
```

Make sure the Git version is **at least** 2.28. If the command is not recognized, reopen the terminal. If it still is not recognized, rerun the installer and make sure **Git from the command line and also from 3rd-party software** is selected.
