# Virtual Environment

- Create virtual environment
  ```sh
  $ python -m venv namavirtualenvironment
  ```
- Active virtual environment
  ```sh
  $ namavirtualenvironment\Scripts\activate
  ```
- Deactive virtual environment
  ```sh
  $ namavirtualenvironment\Scripts\deactivate.bat
  ```

pip is the package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.

- Check package
  ```sh
  $ pip list
  ```
- Upgrading pip
  ```sh
  $ python -m pip install --upgrade pip
  ```
- Install package
  ```sh
  $ pip install <packagename>
  ```
- Create requirement.txt or freeze package
  ```sh
  $ pip freeze > requirement.txt
  ```
