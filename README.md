# chromedriver_auto_installer

## Functionality
 - Automatically download chrome driver
 - Automatically install chrome driver

## Suport OS
 - Linux
 - MacOS
 - Windows

## Installation (Temporarily unavailable)

```
pip install chromedriver_auto_installer
```
or
```
poetry add chromedriver_auto_installer
```

## Usage
```
import chromedriver_autoinstaller
chromedriver_auto_installer.install() 
```

## Example
```
from selenium import webdriver
import chromedriver_autoinstaller


chromedriver_autoinstaller.install()

driver = webdriver.Chrome()
driver.get("http://www.python.org")
```
