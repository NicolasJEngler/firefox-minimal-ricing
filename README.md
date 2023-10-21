# Firefox minimal ricing

This repository contains a collection of configuration files and resources (`userChrome.css` and `userContent.css`) designed to transform Firefox with a sleek and minimalistic user interface. By applying these configurations, you can declutter your Firefox UI, remove unnecessary elements, and enhance your browsing experience.

While modified by myself, most of this config was taken from [penguinFox by p3nguin-kun](https://github.com/p3nguin-kun/penguinFox)

## Installation instructions

To install and use `userChrome.css` and `userContent.css` in Firefox to modify the browser's user interface, follow these step-by-step instructions:

1. **Open Firefox**: Ensure that Firefox is installed and running on your computer.

2. **Access Firefox's Configuration Page**:

   - In the Firefox address bar, type `about:config` and press Enter. This will take you to the Firefox configuration page.
   - You'll see a warning message stating that changing advanced settings can be potentially harmful to the stability, security, and performance of the application. Click "Accept the Risk and Continue" to proceed.

3. **Create a Firefox Profile (Optional)**: It's a good practice to create a new Firefox profile specifically for these modifications. To create a new profile, follow these steps:

   - In the Firefox address bar, type `about:profiles` and press Enter.
   - Under the "Create a New Profile" section, click on "Create Profile." Follow the on-screen instructions to create a new profile. Note the profile name for future reference.

4. **Locate Your Firefox Profile Directory**: You'll need to place the `userChrome.css` and `userContent.css` files in your Firefox profile directory. The location of this directory varies depending on your operating system:

   - **Windows**:
     - The Firefox profile directory can typically be found in `C:\Users\YourUserName\AppData\Roaming\Mozilla\Firefox\Profiles\YourProfileName\chrome`
     - Replace `YourUserName` with your actual Windows username and `YourProfileName` with the name of the Firefox profile you created or your default profile.

   - **macOS**:
     - The directory is usually located at `/Users/YourUserName/Library/Application Support/Firefox/Profiles/YourProfileName/chrome`
     - Replace `YourUserName` with your macOS username and `YourProfileName` with the name of the Firefox profile you created or your default profile.

   - **Linux**:
     - The path is generally `/home/YourUserName/.mozilla/firefox/YourProfileName/chrome`
     - Replace `YourUserName` with your Linux username and `YourProfileName` with the name of the Firefox profile you created or your default profile.

5. **Copy Configuration Files**:

   - Go to the location of your Firefox profile directory, as determined in the previous step.
   - If the `chrome` folder does not exist, create it within the profile directory.
   - Copy the `userChrome.css` and `userContent.css` files you want to use from your local storage to the `chrome` folder in your Firefox profile directory.

6. **Restart Firefox**: Close and reopen Firefox to apply the changes. The modifications specified in `userChrome.css` and `userContent.css` will now be in effect.

Please note that modifications to the `userChrome.css` and `userContent.css` files can significantly alter the appearance and behavior of Firefox. Ensure that you've backed up your original files or that you're comfortable with the changes you're making.

Remember, you can further customize these CSS files to tailor the Firefox UI to your preferences. If you encounter any issues or want to revert to the default appearance, simply remove or rename the modified CSS files in the `chrome` folder.

Enjoy your personalized Firefox browsing experience!