<!--# color
Text Styling Utility for altering terminal text, background colors, and fonts.

```bash
#!/bin/bash

# Define color names
green=$(color green)
red=$(color red)
blue=$(color blue)
magenta=$(color magenta)
cyan=$(color cyan)
yellow=$(color yellow)
white=$(color white)
black=$(color black)

# Define font styles
bold=$(color bold)
italic=$(color italic)
dim=$(color dim)
underline=$(color underline)
blink=$(color blink)
invert=$(color invert)
hidden=$(color hidden)

# Reset 
reset=$(color reset)

# Background color names
bg_red=$(color bg red)
bg_blue=$(color bg blue)
bg_green=$(color bg green)
bg_yellow=$(color bg yellow)
bg_magenta=$(color bg magenta)
bg_cyan=$(color bg cyan)
bg_white=$(color bg white)
bg_black=$(color bg black)

# Example usage
echo "${green}This is ${bold}bold${reset} text in green."
echo "${red}This is ${italic}italic${reset} text in red."
echo "${blue}This is ${underline}underlined${reset} text in blue."
echo "${magenta}This is ${blink}blinking${reset} text in magenta."
echo "${cyan}This is ${dim}dimmed${reset} text in cyan."
echo "${yellow}This is ${invert}inverted${reset} text in yellow."
echo "${white}This is ${hidden}hidden${reset} text in white."
echo "${black}This is ${bold}${red}${bg_green}background${reset} text in black."

# Background color examples
echo "${bg_red}${white}This is text with a red background${reset}"
echo "${bg_blue}${yellow}This is text with a blue background${reset}"
echo "${bg_green}${black}This is text with a green background${reset}"
echo "${bg_yellow}${black}This is text with a yellow background${reset}"
echo "${bg_magenta}${white}This is text with a magenta background${reset}"
echo "${bg_cyan}${black}This is text with a cyan background${reset}"
echo "${bg_white}${black}This is text with a white background${reset}"
echo "${bg_black}${white}This is text with a black background${reset}"

# Reset colors and fonts
echo -e "${reset}Back to normal text"
```-->
