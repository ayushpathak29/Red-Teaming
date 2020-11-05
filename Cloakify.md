# Cloakify

Install CloakifyFactory from [here](https://github.com/TryCatchHCF/Cloakify)

CloakifyFactory transforms any filetype (e.g. .zip, .exe, .xls, etc.) into a list of harmless-looking strings.

## Usage
`$ python cloakifyFactory.py`

**Ciphers** : This Folder contains list of different ciphers in which you want to convert your data.

  ![image](/images/Cloakify/1.png)

- After choosing the cipher and output file, it will convert our file into a normal file with words from cipher.
![image](/images/Cloakify/2.png)

- Using decloakify script with the right cipher name will give us back the original data.
![image](/images/Cloakify/3.png)

- Using NoiseTool we can add noise to our data.

  ![image](/images/Cloakify/4.png)

- To remove Noise from file, we use removeNoise.py script and we have to pass the number of columns we want to remove.
![image](/images/Cloakify/5.png)

- After that, when we again decloakify our file, we'll get back our original data.
![image](/images/Cloakify/6.png)
