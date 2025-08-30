# Lab1.md

## Lab 01

- Name: Braden Henry
- Email: Henry.284@wright.edu

## Part 1 - GitHub Profile

1. [your_github_username_here's GitHub Profile](FIXTHISURL-https://github.com/BradenOSC2004)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |This will bring up manual reference pages       |
| Get-Location | pwd    |Shows your current location within your filing system     |
| Get-ChildItem | ls    |Lists what is in the directory        |
| mkdir   | mkdir       |makes a new directory       |
| Set-Location | cd     |Changes the current directory       |
| New-Item | touch      |Creates new file if it doesnt already exists, file is updated otherwise      |
| Move-Item | mv        |Moves a file      |
| Copy-Item | cp        |Copies a file      |
| Remove-Item | rm      |Removes a file      |
| notepad.exe | vim     | opens up vim        |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: wsl

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: pwd
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir DirB
4. Go into `DirA`: cd DirA
5. Go into `Dir B` from `DirA`: cd DirB
6. Return to your user's home directory: cd 
7. Create a file named `test.txt`: mkdir test.txt
8. Move the file named `test.txt` into `DirA`: mv test.txt DirA
9. Contents of `test.txt`: ls test.txt
```
braden@DESKTOP-8SP7CUN:~$ ls DirA
test.exe  test.txt
braden@DESKTOP-8SP7CUN:~$ ls test.txt
ls: cannot access 'test.txt': No such file or directory
braden@DESKTOP-8SP7CUN:~$

```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp -r test.txt copy.txt
11. View the contents of `DirA`: ls DirA
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: cp -r test.txt fodder.txt
13. Delete / remove both `fodder.txt` AND `Dir B`: rm fodder.txt 
rmdir DirB

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

https://stackoverflow.com/questions/30011267/create-an-empty-file-on-the-commandline-in-windows-like-the-linux-touch-command

https://www.git-tower.com/blog/command-line-cheat-sheet

I also took notes over some commands as went over them in class. 

