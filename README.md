# dotfiles
# Extracter

## Introduction

Extracter is a Python-based GUI application designed to extract complete sentences containing a specific keyword or collocation from a set of text files. The extracted sentences are saved in a new folder named "Extracted" within the source folder, ensuring users can easily access the results. And for the texts without the specific keyword or collocation, a "NA" will be exported.

## Features

- Extracts complete sentences containing a specified keyword or collocation.
- Ensures sentences are fully captured, starting from the nearest capitalized word and ending at the next full stop before a capitalized word.
- Handles text files with UTF-8 and ANSI encoding.
- User-friendly GUI built with Tkinter.
- Saves extracted sentences to a new "Extracted" folder within the source folder.

## Installation

1. Ensure you have Python 3.x installed on your system.
2. Clone or download this repository to your local machine.

## Usage

1. Click the "Choose Files" button to select the original texts.
2. Input the keyword or collocation in the column.
3. Click the "Start Extracting" button and wait for a second.
4. Check the extracted texts in the folder named "Extracted"。
