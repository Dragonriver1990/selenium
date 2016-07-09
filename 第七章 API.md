##  WebDriver API

----------

官方文档连接http://selenium-python.readthedocs.io/api.html#module-selenium.webdriver.chrome.webdriver.

--------

这一章覆盖了Selenium WebDriver所有的接口。

#### Recommmended Import Style

本章定义的接口都是使用类的绝对路径。然而推荐的导入方式使用如下所示：

```python
from selenium import webdriver
```

然后你可以使用如下方式调用类：

```python
webdriver.Firefox
webdriver.FirefoxProfile
webdriver.Chrome
webdriver.ChromeOptions
webdriver.Ie
webdriver.Opera
webdriver.PhantomJS
webdriver.Remote
webdriver.DesiredCapabilities
webdriver.ActionChains
webdriver.TouchActions
webdriver.Proxy
```

特殊的`Keys`类可以通过如下方式导入：

```python
from.selenium.webdriver.common.keys import keys
```

异常类可以通过如下的方式导入（使用明确的类名替换`TheNameOfTheExceptionClass`）。

```python
from selenium.common.exceptions import [TheNameOfTheExceptionClass]
```



