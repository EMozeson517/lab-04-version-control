# lab-04-version-control
Last login: Wed Mar 30 16:37:25 on ttys000
Evans-MacBook-Pro:~ evanmozeson$ pwd
/Users/evanmozeson
Evans-MacBook-Pro:~ evanmozeson$ git status
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ "git add" README.markdown
-bash: git add: command not found
Evans-MacBook-Pro:~ evanmozeson$ README.markdown
-bash: README.markdown: command not found
Evans-MacBook-Pro:~ evanmozeson$ nano README.markdown "git add"
Evans-MacBook-Pro:~ evanmozeson$ git status
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ git add --all
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ git status
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ git commit -m "added a README file"
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ git status
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ git log --color
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ git push origin master
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Evans-MacBook-Pro:~ evanmozeson$ This is lab 04
-bash: This: command not found
Evans-MacBook-Pro:~ evanmozeson$ It's about version control
> git diff --color
> echo "hello"
> 
