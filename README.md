# simpleloopfinder
It's a finder of loops, and a simple one, at that.  Ideal for simple short loops for samplers with limited memory, including vintage samplers.

Use WAV, MP3, AIFF.  Drop a file in and it'll search for three short loops that you can export all three or individually.  Crossfade playback is available to hear what it might sound like with some crossfade added.

### Basic Workflow
1. **Upload**: Click "Upload Audio File" and select your audio
2. **Analyze**: Wait for the automatic loop detection
3. **Review**: Check the detected loops in the "Loop Candidates" section
4. **Preview**: Use Preview buttons to hear each loop
5. **Adjust**: Fine-tune loop boundaries if needed
6. **Export**: Download individual loops or use "Export All"

## Installation Steps

### Step 1: Install Node.js
**Required for running the application**

Choose one method:

#### Method A: Download from Website (Easiest)
1. Go to [nodejs.org](https://nodejs.org/)
2. Download the LTS version for Mac OS
3. Run the installer (.pkg file)
4. Follow the installation wizard

#### Method B: Using Homebrew (For developers)
```bash
# Install Homebrew if you don't have it
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install Node.js
brew install node
```
### Step 2: Run the Application

#### Super Easy Method (Double-Click)
1. Open the `audio-loop-slicer-macos` folder
2. **Double-click** on `Launch Audio Loop Slicer.command`
3. If prompted about security, click "Open"
4. If you get a permission issue, open a terminal window in the application folder and enter: `chmod +x "/path/to/Launch Audio Loop Slicer.command"`
5. The terminal will open and install dependencies automatically
6. Your browser will open with the application at `http://localhost:5173`
