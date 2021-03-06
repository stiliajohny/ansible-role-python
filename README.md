[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL3 License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Ask Me Anything][ask-me-anything]][personal-page]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/stiliajohny/ansible-role-python">
    <img src="https://raw.githubusercontent.com/stiliajohny/ansible-role-python/master/.assets/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">ansible-role-python</h3>

  <p align="center">
    Install Python(3) and pip(3) packages with ease
    <br />
    <a href="./README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/stiliajohny/ansible-role-python/issues/new?labels=i%3A+bug&template=1-bug-report.md">Report Bug</a>
    ·
    <a href="https://github.com/stiliajohny/ansible-role-python/issues/new?labels=i%3A+enhancement&template=2-feature-request.md">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->

## About The Project

### Built With

- Ansible
- Molecule

---

<!-- GETTING STARTED -->

## Getting Started



### Prerequisites

- Ansible

### Installation
```yaml
    - hosts: servers
      roles:
         - { role: ansible-role-python }

```
---

<!-- USAGE EXAMPLES -->

## Usage

```yaml
pip_package: python3-pip
pip_executable: "{{ 'pip3' if pip_package.startswith('python3') else 'pip' }}"

pip_install_packages: []
python_version: "3"
```


---

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/stiliajohny/ansible-role-python/issues) for a list of proposed features (and known issues).

---

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<!-- LICENSE -->

## License

Distributed under the GPL-3.0 License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

John Stilia - stilia.johny@gmail.com


---

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
- [Img Shields](https://shields.io)
- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Pages](https://pages.github.com)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/stiliajohny/ansible-role-python.svg?style=for-the-badge
[contributors-url]: https://github.com/stiliajohny/ansible-role-python/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/stiliajohny/ansible-role-python.svg?style=for-the-badge
[forks-url]: https://github.com/stiliajohny/ansible-role-python/network/members
[stars-shield]: https://img.shields.io/github/stars/stiliajohny/ansible-role-python.svg?style=for-the-badge
[stars-url]: https://github.com/stiliajohny/ansible-role-python/stargazers
[issues-shield]: https://img.shields.io/github/issues/stiliajohny/ansible-role-python.svg?style=for-the-badge
[issues-url]: https://github.com/stiliajohny/ansible-role-python/issues
[license-shield]: https://img.shields.io/github/license/stiliajohny/ansible-role-python?style=for-the-badge
[license-url]: https://github.com/stiliajohny/ansible-role-python/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/johnstilia/
[product-screenshot]: .assets/screenshot.png
[ask-me-anything]: https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg?style=for-the-badge
[personal-page]: https://github.com/stiliajohny
