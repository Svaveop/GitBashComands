# Color Codes for Git Bash

## Overview
This document provides ANSI escape codes for text coloring in Git Bash, making your terminal output more visually appealing and easier on the eyes.

## Color Codes and Their Usage

| Color         | ANSI Code   | Description           |
|---------------|-------------|-----------------------|
| Black         | `\033[30m`   | Standard black        |
| Blue          | `\033[34m`   | Standard blue         |
| Light Blue    | `\033[94m`   | Light blue            |
| Green         | `\033[32m`   | Standard green        |
| Light Green   | `\033[92m`   | Light green           |
| Aqua          | `\033[36m`   | Standard aqua/cyan    |
| Light Aqua    | `\033[96m`   | Light aqua/cyan       |
| Red           | `\033[31m`   | Standard red          |
| Light Red     | `\033[91m`   | Light red             |
| Purple        | `\033[35m`   | Standard purple       |
| Light Purple  | `\033[95m`   | Light purple          |
| Yellow        | `\033[33m`   | Standard yellow       |
| Light Yellow  | `\033[93m`   | Light yellow          |
| White         | `\033[37m`   | Standard white        |
| Bright White  | `\033[97m`   | Bright white          |
| Gray          | `\033[90m`   | Dark gray             |

## Example Usage in Git Bash

You can use these color codes in Git Bash as follows:

```bash
echo -e "\033[30mThis is black text\033[0m"
echo -e "\033[37mThis is white text\033[0m"
echo -e "\033[90mThis is gray text\033[0m"
