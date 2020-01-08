# Promotion extension for Magento 2

Модуль акцій для **Magento 2.3.x**.

Втановлення модулю для подальшої розробки краще виконати за допомогою **Modman Manager**.

- Встановити [modman](https://github.com/colinmollenhour/modman).
  ```
  bash < <(curl -s -L https://raw.github.com/colinmollenhour/modman/master/modman-installer)
  sudo mv ~/bin/modman /usr/local/modman
  ```
- Ініціювати **modman** в кореневій директорії **Magento 2**
  ```
  cd [magento2-root-directory]
  modman init
  ```
- Клонувати репозиторій модулю
  ```
  modman clone https://github.com/victorpetryk/promotion-magento2.git
  ```

Після втановлення модулю за допомогою **Modman Manager**, розробку необхідно виконувати за шляхом `[magento2-root-directory]/.modman/promotion-magento2`.
