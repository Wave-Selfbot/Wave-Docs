# <img src="images/wavesbicon2.ico" alt="Logo" width="35" height="35"> WaveSB Documentation

## Installation

To install the Wave Selfbot, follow these steps:

1. **Download the selfbot**:
   - Visit [waveselfbot.xyz](https://waveselfbot.xyz) and click the "Download" button, or you can [click this link](https://api.celestial.cat/wave/Files/Wave.exe) to download the executable directly.

2. **Create a folder**:
   - Create a folder anywhere on your computer where you want to store the selfbot.

3. **Move the executable**:
   - Place the downloaded executable file into the folder you created.

4. **Run the selfbot**:
   - Run the executable file. When prompted, enter your username, password, and Discord token to start using the selfbot.



## Obtaining Your Discord Token

To use the Wave Selfbot, you will need your Discord token. Follow these steps to obtain it:

1. **Open Discord**:
   - Log in to your Discord account on a web browser (e.g., Chrome, Firefox).

2. **Open Developer Tools**:
   - Right-click anywhere on the page and select **Inspect** or press `Ctrl+Shift+I` (Windows/Linux) or `Cmd+Option+I` (Mac) to open the Developer Tools.

3. **Go to the Network Tab**:
   - In the Developer Tools panel, click on the **Network** tab.

4. **Filter for "XHR"**:
   - In the filter bar, type "xhr" and press Enter. This filters the network traffic to only show XHR requests.

5. **Find the Request Containing Your Token**:
   - Perform any action on Discord (e.g., send a message), and you will see several network requests appear. Click on one of the entries in the list and look for a header named `Authorization`.

6. **Copy Your Token**:
   - The value next to `Authorization` is your Discord token. Right-click on it and select **Copy Value**. Keep this token safe, as it grants access to your Discord account.

## Why Do We Need Your Discord Token?

Wave Selfbot requires your Discord token to interact with your account. The token allows the selfbot to perform actions on your behalf, such as sending messages, managing servers, and executing commands. This ensures that the selfbot can seamlessly integrate with your account and provide all its features.
