📝 Shell Scripting Notes
1. Basic Script Structure
Start with #!/bin/bash (shebang) to define the script interpreter.

Use echo to print messages to the terminal.

2. Creating Directories and Files
mkdir is used to make a new directory.

cd changes the current working directory.

touch creates new files.

ls lists files in a directory.

3. Installing Packages
sudo apt update refreshes the package list.

sudo apt install <package> installs a package (e.g., cowsay).

4. Using Installed Programs
Once installed, programs like cowsay can be run directly with input strings.

5. Creating Users from a Script
Use a for loop to iterate over a list of usernames.

adduser adds a new user.

Use --disabled-password and --gecos "" for minimal user info.

6. Creating Zip Backups
Use zip -r to create a zipped backup of a folder.

7. Setting Up Cron Jobs
crontab -e opens the cron editor.

A typical cron line: 0 * * * * /path/to/script.sh runs the script every hour.

8. Loops
Use a for loop to repeat a set of commands.

$i represents the current item in the loop.

9. Passing Arguments to Scripts
$0 is the script name.

$1, $2, etc., are arguments passed when running the script.
