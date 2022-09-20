<h1 align="center">Welcome to Slimbook Service 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.2-blue.svg?cacheSeconds=2592000" />
  <a href="https://www.gnu.org/licenses/gpl-3.0.html" target="_blank">
    <img alt="License: GPL--3+" src="https://img.shields.io/badge/License-GPL--3+-yellow.svg" />
  </a>
  <a href="https://twitter.com/SlimbookEs" target="_blank">
    <img alt="Twitter: SlimbookEs" src="https://img.shields.io/twitter/follow/SlimbookEs.svg?style=social" />
  </a>
</p>


# slimbook-qc71-dkms

Page under construction.
Module adaptation of pobrn qc71_laptop to DKMS.
Added support for our Slimbook laptops.

slimbook-qc71 driver in DKMS format.

Slimbook service implementation and adaptation of [pobrn/qc71_laptop](https://github.com/pobrn/qc71_laptop)

# Install
```shell
   sudo apt-add-repository ppa:slimbook/slimbook
   sudo apt install slimbook-qc71-dkms
```
After installing, if module does not load automatically, you can reboot or load module manually:
```
sudo modprobe qc71_laptop
```



### 🏠 [Homepage](https://github.com/slimbook/slimbookrgbkeyboard)

## Author

- [@marslimbook](https://www.github.com/marslimbook)

👤 **Slimbook**

* Website: https://slimbook.es
* Twitter: [@SlimbookEs](https://twitter.com/SlimbookEs)
* Instagram: [@slimbookes](https://www.instagram.com/slimbookes/)
* Github: [@slimbook](https://github.com/slimbook)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Slimbook-Team/slimbook-qc71-dkms/issues). 

## Show your support

Give a ⭐️ if this project helped you!

<a href="https://www.patreon.com/slimbook">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## 📝 License

Copyright © 2022 [Slimbook](https://github.com/slimbook).<br />
This project is [GPL--3+](https://www.gnu.org/licenses/gpl-3.0.html) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
