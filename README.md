# color
Text Styling Utility for altering terminal text, background colors, and fonts.

* [Example of Code](#code)
<img src="https://gh05t-hunter5.github.io/the-source/color/IMG_20230822_113611.jpg">

This library integrates seamlessly with your toolkit, enhancing color schemes, backgrounds, and fonts. It simplifies the process by eliminating the need to manually learn and input color codes. With a simple import, you can leverage the capabilities of this library to elevate your design aesthetics.

## INSTALLATION

### Linux 

```wget https://gh05t-hunter5.github.io/the-source/color/color.sh && sudo bash color.sh```

### Termux 

```wget https://gh05t-hunter5.github.io/the-source/color/color.sh && bash color.sh```

## About Color Package

Welcome to the Color Package, a dynamic text styling utility designed to transform your terminal experience. With an array of customizable options, this package empowers you to curate a workspace that aligns with your preferences and enhances your productivity.

### Elevate Your Terminal Experience

Unleash the potential of your Linux environment with the Color Package:

- **Personalized Aesthetics**: Infuse your terminal with vibrant hues that resonate with you. From the rich depths of your favorite colors to the calming influence of distinct backgrounds, our package lets you make the terminal truly yours.

- **Team Unity**: Seamlessly integrate your team's identity into the terminal. Customize colors and fonts to reflect your collective spirit and create a unique, shared workspace.

- **Immersive Atmosphere**: Set the mood by changing the terminal's background color. Create an atmosphere that aligns with your workflow, from serene focus to energized creativity.

- **Auditory Enhancement**: Elevate your interactions with auditory cues. Adjust terminal sounds to add a layer of engagement to your command-line activities.

### Unveiling Infinite Possibilities

The Color Package isn't just about aesthetics; it's about optimizing your Linux experience:

- **Aesthetics and Functionality**: Enhance readability and visual appeal simultaneously, ensuring that style never compromises substance.

- **Organization Made Simple**: Employ color and font variations to streamline information presentation, making every interaction clear and intuitive.

- **Productivity Amplified**: Craft an environment that boosts focus and productivity. Choose colors that stimulate your mind or backgrounds that encourage deep concentration.

### Embrace the Future of Linux Interaction

Don't miss the chance to revolutionize your Linux journey. Installing the Color Package via Termis and other Linux-based applications is all it takes to unlock a new level of customization and innovation. Experience firsthand the transformation that awaits you. Seize the opportunity to immerse yourself in an environment that not only works for you but resonates with your individuality.

Your Linux journey, enhanced by the Color Package, is just a step away. Embark on this journey today and make your terminal truly your own.

### Code
## Usage

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
```
