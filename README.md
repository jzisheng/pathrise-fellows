# pathrise-fellows
**Automatic connect and endorse**

### Instructions for installation: 

Make sure to download the appropriate chromedriver [here](https://chromedriver.chromium.org/downloads)

For MacOS, install of chromedriver through homebrew (recommended) 

`brew cask install chromedriver`

For authentication, create a new directory:
`resources/`

Store the CSV here, as well as authenticaiton details in `resources/auth.txt` as follows:

```
your@email.com

yourPassword
```

### Running:

In commandline run `python3 script.py resources/auth.txt resources/fellows.csv`, this should start the selenium chrome driver, log in using `resources/auth.txt`, and iterate through `resources/fellows.csv`


### Requirements
 * python3
 * panda
 * selenium webdriver(chrome)
