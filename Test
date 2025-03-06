from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
import pyperclip

# Инициализация драйвера
driver = webdriver.Chrome()

# Открытие страницы
driver.get("https://www.google.ru/?hl=ru")

# Поиск элемента
element = driver.find_element(By.ID, "APjFqb")
element.send_keys("Машина")
element.send_keys(Keys.ENTER)
# button_element = driver.find_element(By.CLASS_NAME, "gNO89b")
# button_element.click()

# Получение текста из элемента
# text_to_copy = element.text
# print("Текст для копирования:", text_to_copy)

# Копирование текста в буфер обмена
# pyperclip.copy(text_to_copy)

# Проверка: вставка текста из буфера обмена
# pasted_text = pyperclip.paste()
# print("Текст из буфера обмена:", pasted_text)

# Закрытие браузера
# driver.quit()