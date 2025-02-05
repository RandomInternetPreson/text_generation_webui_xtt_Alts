
# Install from the Original Repo:
https://github.com/kanttouchthis/text_generation_webui_xtts

# Example
This tooke about 3 seconds to render on a 4090
![ouput](https://github.com/RandomInternetPreson/text_generation_webui_xtt_Alts/assets/6488699/cbcf7952-93bb-4ec9-8540-53e38baf310a)

https://github.com/RandomInternetPreson/text_generation_webui_xtt_Alts/assets/6488699/a455b6ff-a6c4-41a0-abed-65f37bf6dd90

# The orignal repo should be compatible with winodows now, install from there:
Orignial Repo: https://github.com/kanttouchthis/text_generation_webui_xtts
 use these instructions if you need help installing extensions

# Installation (Windows)

https://github.com/RandomInternetPreson/text_generation_webui_xtt_Alts/assets/6488699/30185557-d9ec-431d-bf56-20ffbaa0bd31

Clone this repo with git or clone using the text-generation-webui software:
```
git clone https://github.com/kanttouchthis/text_generation_webui_xtts
or just enter the url in the "Install or update an extension" window in the "Session" tab (remember to press enter):
https://github.com/kanttouchthis/text_generation_webui_xtts
```
Activate your environment.
```
Go to the install folder where you unzipped the one-click installer, and click on cmd_windows.bat
```
Install dependencies for TTS.
```
Via the command window that has now popped up, navitate to the text_generation_webui_xtt extension in the "extensions" folder in the textgen install directory.  To do this enter:

cd your-directory-here

cd means change directory, and your directory will look something like this: L:\OobNov13\text-generation-webui-main\extensions\text_generation_webui_xtt
so you would put "cd L:\OobNov13\text-generation-webui-main\extensions\text_generation_webui_xtt" in the command window (without the quotes)

Once you have navigated to the install directory for the extension from the perspective of the command window enter the following:

pip install -r requirements.txt
```
Install TTS. Their version requirements cause issues so we install the dependencies above, without version requirements.
```
With the command window still open (reopen it if you have closed it) enter the text below:
pip install TTS --no-dependencies
```


# Installation
Clone this repo:
```
cd extensions
git clone https://github.com/kanttouchthis/text-generation-webui-xtts
```
Activate your environment. For example:
```
conda activate textgen
```
Install dependencies for TTS.
```
pip install -r requirements.txt
```
Install TTS. Their version requirements cause issues so we install the dependencies above, without version requirements.
```
pip install TTS --no-dependencies
```

# Usage
Once you finished the steps above, you can add some voices to the voices folder. This can be any short (3-6 seconds) wav clip of someone talking. Make sure it's high quality audio with no long gaps.
Then, run the webui with `--extensions xtts` and select your voice/language and other settings at the bottom. You might have to accept the terms and conditions via the console when you first run it.
