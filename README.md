<h1 align="center">
  <a href="https://github.com/sureserverman/adminitools">
    <!-- Please provide path to your logo here -->
    <img src="docs/images/logo.svg" alt="Logo" width="100" height="100">
  </a>
</h1>

<div align="center">
  Admin mini tools
  <br />
  <a href="#about"><strong>Explore the screenshots »</strong></a>
  <br />
  <br />
  <a href="https://github.com/sureserverman/adminitools/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
  ·
  <a href="https://github.com/sureserverman/adminitools/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a>
  .
  <a href="https://github.com/sureserverman/adminitools/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+">Ask a Question</a>
</div>

<div align="center">
<br />

[![Project license](https://img.shields.io/github/license/sureserverman/adminitools.svg?style=flat-square)](LICENSE)

[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/sureserverman/adminitools/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![code with love by sureserverman](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-sureserverman-ff1414.svg?style=flat-square)](https://github.com/sureserverman)

</div>

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Project assistance](#project-assistance)
- [Authors & contributors](#authors--contributors)
- [Security](#security)
- [License](#license)

</details>

---

## About

> This set of tools was made to simplify and automate some daily tasks of linux administrators. It includes **logtail** for extraction relevant information from ***/var/log/syslog***, 
> **stripconf** to get info on only active settings from ***.conf*** files, **hist-filter** for those who hate pressing ***Ctrl-R*** multiple times while looking for particular command in ***history***,
> **hist-switch** to turn bash history ***on/off***
> If you have any ideas about what to add to this set, feel free to create an issue or a pull request

### Built With

> Pure bash and bash only. No strings attached. Thus it can be installed to any debian-based liux distro and any architecture

## Getting Started

### Installation

> `git clone https://github.com/sureserverman/adminitools.git`\
> `dpkg-deb --build adminitools`\
> `sudo dpkg -i adminitools`


## Usage

> `logtail -h` or `logtail --help` - to print help\
> `logtail` without arguments to print help again\
> `logtail argument1 argument2...` with as many arguments as you need\
> where argument should be substring that you want to find from your log\
> The output is last 50 lines from log, which contain *argument1* substring, then\
> after key pressed by the user, last 50 lines from log, which contain *argument2* substring etc.
> 
> `stripconf -h` or `stripconf --help` - to print help\
> `stripconf` without arguments to print help again\
> `stripconf argument1 argument2...` with as many arguments as you need\
> where argument should be name of the file, which contains configuration information
> 
> `hist-filter -h` or `hist-filter --help` - to print help\
> `hist-filter` without arguments to print help again\
> `hist-filter argument1 argument2...` with as many arguments as you need\
> The output will be last 50 commands from bash history, that contain *argument1*\
> Then it waits for any key to be pressed by you and prints out last 50 commands, that contain *argument2* etc
> 
> `histswitch -h` or `histswitch --help` - to print help
> `histswitch` without arguments to enable history when disabled and disable when enabled
> `histswitch yes` to enable history
> and `histswitch no` to disable history
> The settings are stored in /etc/hist/enable file

## Roadmap

See the [open issues](https://github.com/sureserverman/adminitools/issues) for a list of proposed features (and known issues).

- [Top Feature Requests](https://github.com/sureserverman/adminitools/issues?q=label%3Aenhancement+is%3Aopen+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Top Bugs](https://github.com/sureserverman/adminitools/issues?q=is%3Aissue+is%3Aopen+label%3Abug+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Newest Bugs](https://github.com/sureserverman/adminitools/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

## Project assistance

If you want to say **thank you** or/and support active development of Admin mini tools:

- Add a [GitHub Star](https://github.com/sureserverman/adminitools) to the project.
- Tweet about the Admin mini tools.
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

Together, we can make Admin mini tools **better**!

## Authors & contributors

The original setup of this repository is by [Serverman](https://github.com/sureserverman).

For a full list of all authors and contributors, see [the contributors page](https://github.com/sureserverman/adminitools/contributors).

## Security

Admin mini tools follows good practices of security, but 100% security cannot be assured.
Admin mini tools is provided **"as is"** without any **warranty**. Use at your own risk.

_For more information and to report security issues, please refer to our [security documentation](docs/SECURITY.md)._

## License

This project is licensed under the **GPLv3 license**.

See [LICENSE](LICENSE.md) for more information.
