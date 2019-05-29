# ComputerVision-ImageAnalyzer
A sample REST call to Microsoft's cognitive AI service called Computer Vision for analyzing images

## Prerequisites
You must have Python installed if you want to run the sample locally.
You must have a subscription key for Computer Vision. You can get a free trial key from Try Cognitive Services. Or, follow the instructions in Create a Cognitive Services account to subscribe to Computer Vision and get your key.
You must have the following Python packages installed. You can use pip to install Python packages.<br>
<b>1. requests<br>
2. matplotlib<br>
3. pillow</b><br>

Install the above packages using <b>pip</b> e.g.<br>
<code>pip install requests</code><br>

## Create and run the sample<br>
### Make the following changes in code where needed:
1. Replace the value of <code>subscription_key</code> with your subscription key.<br>
2. Replace the value of <code>vision_base_url</code> with the endpoint URL for the Computer Vision resource in the Azure region where you obtained your subscription keys, if necessary.<br>
3. Optionally, replace the value of <code>image_url</code> with the URL of a different image that you want to analyze.<br>
4. Save the code as a file with an .py extension. For example, analyze-image.py.<br>
5. Open a command prompt window.<br>
6. At the prompt, use the python command to run the sample. For example, python analyze-image.py.<br>
