# Lethal's Filterlists

These are random filter lists that I found and wanted to maintain them for personal use

Feel free to use anything here!

## Installation

  - Go to Pi-Hole adlists tab
  - Copy and paste into the textbox:
  
  ```
  https://raw.githubusercontent.com/LethalAspect/filterlists/main/iphosts.txt
  ```
  OR
    ```
  https://raw.githubusercontent.com/LethalAspect/filterlists/main/ipadblock.txt
  ```
  
  - Click the Add button
  - Lastly do `pihole -g` to update your list

## To-Do/Enhancements
- [x] Add support for domains starting in WWW
- [ ] Check if domains are alive or dead and place them in the right placement
- [ ] Automate proccess of adding new domains
- [ ] Add new filter lists
- [x] Organize the list for better look

# Credits
[To Piperun for original iphosts.txt](https://github.com/piperun/iploggerfilter)
