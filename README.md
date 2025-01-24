# Dataset
All emojis are designed by [OpenMoji](https://openmoji.org/) – the open-source emoji and icon project. License: CC BY-SA 4.0  
Original link: https://github.com/hfg-gmuend/openmoji/releases/latest/download/openmoji-72x72-color.zip

The emoji image is 72 * 72 pixels with 10 pixels of meaningless margin on both sides of rows and columns.  
The images of the emojis after cropped are 52 * 52 pixels.  

# Run-time Environment
All the code is in form of **Jupyter Notebook** and it was programmed in the **Google Colab**. The file `requirements.txt` contains the specific version of each Python library used.  

The Python standard libraries imported in this code are the default versions provided by Google Colab. However, as time passes, Google Colab's default Python standard library might update to newer versions, potentially deprecating older libraries and causing incompatibility or conflicts. Therefore, after testing the code, I added the following code to prevent conflicts.  

**Set up Environment for the model based on TensorFlow**   
`!pip install -r https://raw.githubusercontent.com/caochengrui/Object_Classification_and_Localiztion_on_Emoji_Dataset/refs/heads/main/PyTorch/requirements.txt`  

**Set up Environment for the model based on PyTorch**  
`!pip install -r https://raw.githubusercontent.com/caochengrui/Object_Classification_and_Localiztion_on_Emoji_Dataset/refs/heads/main/PyTorch/requirements.txt` 

Please ensure that specific versions of the libraries are installed when running the code.

### TensorFlow Directory
The code was programmed using TensorFlow.  

### PyTorch Directory
The code was programmed using PyTorch.  
