# Game Binary Templates for 010 Editor

> **Open Source Alternative Available**: If you're looking for an open source alternative, check out my [ImHex-Game-Patterns-Collection](https://github.com/ModzabazeR/ImHex-Game-Patterns-Collection) - A collection of game binary patterns for [ImHex](https://imhex.werwolv.net/), a free and open-source hex editor that serves as an alternative to 010 Editor templates.

This repository contains a collection of binary templates (.bt files) for analyzing and editing video game binary files using [010 Editor](https://www.sweetscape.com/010editor/).

## What are .bt Templates?

010 Editor binary templates (.bt files) are scripts written in a C-like language that define the structure of binary files. They allow you to:

- Visualize complex binary data in a structured, human-readable format
- Understand the layout and organization of game files
- Edit binary data with proper context and validation
- Reverse engineer game file formats

These templates act as a map for interpreting raw binary data, making it possible to understand and modify game assets without specialized tools.

## Included Templates

This repository includes templates for the following games:
- [Bioforge](Bioforge/README.md)
- [Steins;Gate](SteinsGate/README.md)

## Installation

1. Install [010 Editor](https://www.sweetscape.com/010editor/) (commercial software with free trial)
2. Clone or download this repository
3. In 010 Editor, go to **Templates > View Installed Templates...**
4. Click **Add...** and navigate to the folder containing these templates
5. Select the templates you want to install and click **Open**

## Usage

1. Open a binary file in 010 Editor
2. Press F5 or go to **Templates > Run Template...**
3. Select the appropriate template for your file type
4. The file structure will be displayed in the Template Results panel

For example, to analyze a Steins;Gate MPK archive:
1. Open the .mpk file in 010 Editor
2. Run the MPK.bt template
3. Browse the structured data in the Template Results panel

## Contributing

Contributions are welcome! If you have templates for additional games or improvements to existing templates:

1. Fork this repository
2. Add or modify templates
3. Submit a pull request

When creating new templates, please:
- Include comments explaining the file format
- Document the purpose of each structure
- Test thoroughly with multiple files
- Include the game name as a prefix in the filename

## Related Projects

- [ImHex-Game-Patterns-Collection](https://github.com/ModzabazeR/ImHex-Game-Patterns-Collection) - A collection of game binary patterns for [ImHex](https://imhex.werwolv.net/), an open-source hex editor. This repository serves as an open-source alternative to 010 Editor templates.

## Resources

- [010 Editor Binary Templates Documentation](https://www.sweetscape.com/010editor/manual/IntroTempScripts.htm)
- [Binary Templates Repository](https://www.sweetscape.com/010editor/repository/templates/)

## Acknowledgements

This repository contains a mix of original templates created by me, contributors, and templates adapted from the game modding and reverse engineering communities. Thanks to these communities for their research and documentation of various file formats that made some of these templates possible.
