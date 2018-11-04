# Google Spreadsheets Formula: sokuid
## Description
SOKUID stands for:
* SO:  Sistema Operavito (from spanish Operating System)
* K:   From luck (the letter K)
* UID: Relating term to UUID, because of its essence

The formula is designed to generate a random "unique"&#42;  identifyer for usage within your 
spreadsheets and/or databases.

## How to use
### Step 1
Copy the formula from the `main.google.spreadsheets.formula` file.
The content of the file is the formula only.
Quicktrick for MacOS:
```bash
cd /path/to/directory/
cat ./main.google.spreadsheets.formula | pbcopy 
```
### Step 2
Now you can paste using either your regular methods
or by doing this if you need to put it somewhere else:
#### On MacOS
```bash
cd /path/to/your/destination/or/whatever
pbpaste
```
#### On Linux:
First make sure you have xsel installed (for debian just do `sudo apt-get install xsel`.
Then do this  BEFORE the MacOS steps, and then just follow the MacOS steps within 
your Linux bash terminal or emulator.
```bash
echo "alias pbcopy=\"tr -d '\n' | xsel --clipboard --input\"" >> ~/.bashrc
echo "alias pbpaste="xsel --clipboard --output"" >> ~/.bashrc
source ~/.bashrc
```
## DISCLAIMER
This formula does not guarrantee any uniqueness and it is recommended to ALWAYS analyse 
the formula before making any business decisions. -warned you are- -lu1s.github.

