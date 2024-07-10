## Text to ASCII Art 
![Go-Logo_Blue-removebg-preview(2)](https://github.com/makebelief/makebelief/assets/166484145/ad53f422-f338-4dd7-9ef1-ab772aa1fbb5)
### Overview

This project is an ASCII art program implemented in Go. It takes a string as input and outputs a graphic representation of the string using ASCII characters. The output resembles the input string but with ASCII characters.
### Content
- main.go

- printart.go
- readbyline.go
- readtxtfile.go
- validate.go
- handlers_test.go
- shadow.txt
- standard.txt
- thinktoy.txt
### Features

- Handles input with numbers, letters, spaces and newlines.
- Supports various graphical templates using ASCII characters.
- Written in Go with adherence to good practices.
- Includes test files for unit testing.￼ 
### Limitations and Error Handling
- Our program does not handle cases where special characters (0-32) are part of the input string, instead it returns an error message.
- Also non-ascii characters (>128) are not included in the scope of this program they also generate error message when found in the input.

### Banner Formats

The ASCII banner files included in the project have specific graphical representations formatted in ASCII. Each character has a height of 8 lines, and characters are separated by a newline (\n) character.

The following banner formats are included:
- `shadow`
- `standard`
- `thinkertoy`

### How to Install
Ascii-art requires [go](https://go.dev/dl/)  v 1.22.2 to run

Once go is installed  clone into this repository to do this 

- Open terminal and run
``` sh
git clone https://github.com/skanenje/ascii-art
cd ascii-art
```

### Usage
Once you are in the directory,

To run the program, use the following command, on the terminal command line:

the ascii art representation is by default printed in the standard font.

```bash
go run . "<your_string>"
```

For example:

```bash
go run . "Hello\\nthere"
```
To print ascii art from different font file, we have utilised flags to use them
```bash
go run . "<your string>" -th
```
for thinkertoy font. and,
```bash
go run . "<your string>" -sh
```
for shadow font.

### Example Outputs

Here are some example outputs generated by the program:

The default format

```
 _    _          _   _          
| |  | |        | | | |         
| |__| |   ___  | | | |   ___   
|  __  |  / _ \ | | | |  / _ \  
| |  | | |  __/ | | | | | (_) | 
|_|  |_|  \___| |_| |_|  \___/  
                                 
                                       
```
in thinkertoy font
```
o        o o     
|        | |     
O--o o-o | | o-o 
|  | |-' | | | | 
o  o o-o o o o-o 
                 
```
in shadow font 
```
_|                _| _|          
_|_|_|     _|_|   _| _|   _|_|   
_|    _| _|_|_|_| _| _| _|    _| 
_|    _| _|       _| _| _|    _| 
_|    _|   _|_|_| _| _|   _|_|   
                                
```
### Allowed Packages

Only standard Go packages are used in this project.





## HOW TO CONTRIBUTE ? 👷 

**1.** Fork [this](https://github.com/skanenje/ascii-art) repository.

**2.** Clone the forked repository.

```terminal
git clone https://github.com/skanenje/ascii-art
```

**3.** Navigate to the project directory.

```terminal
cd ascii-art
```

**4.**  MAKE A NEW FOLDER WITH YOUR PROJECT NAME INSIDE 
<br>

**5.**  Also Add a README file in your project folder which consists of Description/screenshots about your project !
          
 
<br>

**6.** Create a new branch.

```terminal
git checkout -b <your_branch_name>
```

**7.** Add & Commit your changes.

```terminal
  git add .
  git commit -m "<your_commit_message>"
```

**7.** Push your local branch to the remote repository.

```terminal
git push -u origin <your_branch_name>
```

**8.** Create a Pull Request!

**Congratulations!** Sit and relax till we review your PR, you've made your contribution to (https://github.com/skanenje/ascii-art) project

### Issues and Contributions

If you encounter any issues or have suggestions for improvements, feel free to submit an issue or propose a change.

## Enjoy ASCII Art in Go!

Feel free to explore the codebase, run the program with different inputs, and contribute to enhancing the project. Happy coding experience!
### Contributors

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://www.linkedin.com/in/swabri-musa-565350291?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Buf0Ls4oWR2O2WLUMO5sIBg%3D%3D>
            <img src=https://learn.zone01kisumu.ke/git/avatars/bc7899a0aac2630a0a9b50bf330437a7?size=870 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Aaron/>
            <br />
            <sub style="font-size:14px"><b>skanenje</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://www.linkedin.com/in/rodgers-kaunda>
            <img src=https://learn.zone01kisumu.ke/git/avatars/aa19095145ab1ad43695e3cd3f7f3a5b?size=870 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Emmanuel/>
            <br />
            <sub style="font-size:14px"><b>krodgers</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://www.linkedin.com/in/shayo-victor-381370307?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BVqNrlq5mTZS8tPMy8%2FIuUQ%3D%3D>
            <img src=https://learn.zone01kisumu.ke/git/avatars/53f5cf6826e2e5aa726c95e3873d931d?size=870 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Abraham/>
            <br />
            <sub style="font-size:14px"><b>svictor</b></sub>
        </a>
    </td>
</tr>
</table>
