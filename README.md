# pathrise-fellows
**Automatic connect and endorse**

![Alt Text](https://github.com/jzisheng/pathrise-fellows/blob/testing/demo.gif)

### Instructions for installation: 

Make sure to download the appropriate chromedriver [here](https://chromedriver.chromium.org/downloads)

For MacOS, install chromedriver through homebrew (recommended) 

`brew cask install chromedriver`

For authentication, create a new directory:
`resources/`

Store the CSV here, as well as authenticaiton details in `resources/auth.txt` as follows:

```
your@email.com

yourPassword
```

### Running:

In commandline run `python3 script.py`, this should start the selenium chrome driver, log in using `resources/auth.txt`, and iterate through `aresources/fellows.csv`


### Requirements
 * python3
 * panda
 * selenium webdriver(chrome)
