# Automation-Training- Naveen Kumar - 212223220067
Automates filling and submitting a web form using Selenium with Python by locating elements through Name and ID, entering data, and clicking options.

### Selenium Form Automation with Python

### Project Overview

This project demonstrates web form automation using Selenium with Python.
The automation script opens a demo website using Microsoft Edge, identifies form elements using Name and ID locators, enters user information, selects options, and fills the complete form automatically.
This project was created as part of Selenium and QA Automation practice.

## code

```
from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Edge()

driver.get("https://vinothqaacademy.com/demo-site/")


time.sleep(5)
driver.find_element(By.NAME, "vfb-5").send_keys("Naveen")

time.sleep(2)
driver.find_element(By.NAME, "vfb-7").send_keys("Kumar")

time.sleep(2)
driver.find_element(By.ID, "vfb-31-1").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-20-0").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-20-4").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-20-2").click()

time.sleep(2)
driver.find_element(By.ID, "vfb-13-address").send_keys("2/460 church street")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-address-2").send_keys("Ambedkar Nagar, manapakkam")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-city").send_keys("Chennai")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-zip").send_keys("600125")

time.sleep(2)
driver.find_element(By.ID, "vfb-13-state").send_keys("TAMIL NADU")

time.sleep(2)
driver.find_element(By.ID, "vfb-14").send_keys("natarajkumaran26@gmail.com")

time.sleep(15)
```

## Output
<img width="1569" height="956" alt="image" src="https://github.com/user-attachments/assets/bb50a1a1-368c-4bf5-92d0-956fe674df44" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/99c3c1ef-53e7-4811-901a-9a1685148d43" />

