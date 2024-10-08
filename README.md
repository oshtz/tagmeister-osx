# tagmeister <img src="https://github.com/oshtz/tagmeister-osx/blob/main/tagmeister/Assets.xcassets/AppIcon.appiconset/AppIcon256%201.png?raw=true" alt="tagmeister logo" width="128" align="right"/>

tagmeister is a macOS application designed for efficient image captioning, primarily aimed at dataset preparation for machine learning projects.

## Features

- Browse and select images from a chosen directory
- Generate captions for images using OpenAI vision capable models
- Edit and customize generated captions with auto-save
- Batch processing for multiple images
- Prepend and append text to generated captions
- Captions created in .txt format with the same name as the image file
- Dark mode support for comfortable extended use
- Customizable font size for better readability

## Requirements

- macOS 14.5 or later
- Xcode 15.4 or later (for development)
- OpenAI API key for caption generation

## Installation

### Option 1: Download and Install DMG

1. Go to the [Releases](https://github.com/oshtz/tagmeister/releases) page of the tagmeister repository.
2. Download the latest `tagmeister.Installer.dmg` file.
3. Open the downloaded DMG file.
4. Drag the tagmeister app to your Applications folder.
5. Eject the DMG and launch tagmeister from your Applications folder.

### Option 2: Build from Source

1. Clone the repository:
   ```
   git clone https://github.com/oshtz/tagmeister.git
   ```
2. Open the project in Xcode:
   ```
   cd tagmeister
   open tagmeister.xcodeproj
   ```
3. Build and run the project in Xcode.

## Usage

1. Launch tagmeister.
2. Click "Select Directory" to choose a folder containing your dataset images.
3. Browse through your images using the left sidebar.
4. Customize caption generation settings in the settings panel.
5. Use batch processing for efficient captioning of multiple images.

## Configuration

### API Key

To use tagmeister, enter your API key in the designated field.

## Development

### Project Structure

Key components of the project:

- `ContentView.swift`: Main view of the application
- `AutoCaptionerView.swift`: Handles the auto-captioning functionality

### Building the Project

1. Ensure you have Xcode 15.4 or later installed.
2. Open the project in Xcode.
3. Click the "Run" button or press `Cmd + R` to build and run the project.

## Contributing

Contributions to tagmeister are welcome! Please feel free to submit a Pull Request.
