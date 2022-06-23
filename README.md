# How to set timezone to an automation test in Python-selenium on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Python-selenium-timezone)

If you want to run you automation test for a particular timezone in Python-selenium on Lambdatest, you can use the following steps. You can refer to sample test repo [here](https://github.com/LambdaTest/python-selenium-sample).

# Steps:

To run your automation test for a particular timezone, you can change the timezone using the 'timezone' capability. For example, setting timezone to "UTC-5:00":


```python
desired_caps = {
            'LT:Options': {
                "build": "Python Demo",  # Change your build name here
                "name": "Python Demo Test",  # Change your test name here
                "platformName": "Windows 11",
                "selenium_version": "4.0.0",
                "timezone": "UTC-05:00"
            },
            "browserName": "Chrome",
            "browserVersion": "98.0",
        }

```

For the full list of available capabilities, you can refer [here](https://www.lambdatest.com/support/docs/selenium-automation-capabilities/).

### Run your test

```bash
python lambdatest.py
```

# Links:

[LambdaTest Community](http://community.lambdatest.com/)

