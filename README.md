**This script assumes you've filled one myworkdayjobs application out and you have some stored filled in information** *no it does not anymore uh haha*

# Purpose
The purpose of this project is to have a script that runs somewhat well on job applications that use myworkdayjobs as the application host, will potentially be able to fill in any personal information using info.txt as well as fill in many of the boxes using selenium 

# How to install
- make sure python3 is installed, if not installed by default: on linux use your package manager `yay -S python3`, if windows use the .exe on the site and add to path, if mac use homebrew
- same thing applies for pip, same steps as well, 

# this is not right 
- `yay -S python3-pip`

# this is
- once pip is installed, use pip to install selenium `pip3 install selenium`
- then install jupyter to test your code in nice segments `pip3 install jupyter`

# How to run
- `./workdayjobs {url} {txt_file_with_info}`