<h1 align="center">
    debget
</h1>

Install software with non-root privilege, can work on debian-based distribution.

### how to

- Get and install debget

  ```sh
  wget -O debget https://github.com/wxjstz/debget/raw/main/debget
  chmod +x debget
  ./debget
  source ~/.apt/rc
  ```

- Install new software

  ```sh
  debget pkg1 pkg2 ...
  ```

- View the log of debget

  ```sh
  cat ~/.apt/log.txt
  ```
