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

> This set of bash-scripts was made to simplify routine of basic deployment of VPS with Ubuntu 22.04 installed
> It includes creating user with randomly generated name, adding public keys of VPS admin (if you setting up server for someone else to administer),
> Changing ssh port to randomly generated and decreasing verbosity1 of ssh banners, disabling root access to ssh as well as password access,
> setting up fail2ban for ssh and honeypot on port 22, closing all but nesessary ports with UFW firewall, setting up some applicatios, such as
> Matrix-server synapse with slidig-sync and behind Caddy reverse-proxy or XRay/VLESS proxy server

### Built With

> Pure bash and bash only. No strings attached. Thus it can be installed to any debian-based liux distro and any architecture

## Getting Started

### Installation

> Just copy this set of scripts to the root directory of VPS 

## Usage

> This script usage: init.sh -[hvdUKPBtSmcxRparbHuf]\
> Flags determine everything\
> Install: Matrix -m, Caddy -c, Xray -x <fake_domain>, SSH honeypot -H, TOR -t, socat -S\
> Set up UFW -u, Fail2ban -f, New user -U, verbosity -v <0|1|2|3|4>, domain name -d <domain_name>, .onion service for ssh port -P\
> SSH options: Custom port -p, Disable root login -r, Disable banners verbosity1 -b, Disable unsafe authentication methods -a\
> -h or no flags Print this help\
> -B to set as backend server\
> -K to add client's public key for ssh
>
> 

## Roadmap

See the [open issues](https://github.com/sureserverman/adminitools/issues) for a list of proposed features (and known issues).

- [Top Feature Requests](https://github.com/sureserverman/adminitools/issues?q=label%3Aenhancement+is%3Aopen+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Top Bugs](https://github.com/sureserverman/adminitools/issues?q=is%3Aissue+is%3Aopen+label%3Abug+sort%3Areactions-%2B1-desc) (Add your votes using the 👍 reaction)
- [Newest Bugs](https://github.com/sureserverman/adminitools/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

## Project assistance

If you want to say **thank you** or/and support active development of Bootstrap scripts for easy server setup:

- Add a [GitHub Star](https://github.com/sureserverman/adminitools) to the project.
- Tweet about the Bootstrap scripts for easy server setup.
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

Together, we can make Bootstrap scripts for easy server setup **better**!

## Authors & contributors

The original setup of this repository is by [Serverman](https://github.com/sureserverman).

For a full list of all authors and contributors, see [the contributors page](https://github.com/sureserverman/adminitools/contributors).

## Security

Bootstrap scripts for easy server setup follows good practices of security, but 100% security cannot be assured.
Bootstrap scripts for easy server setup is provided **"as is"** without any **warranty**. Use at your own risk.

_For more information and to report security issues, please refer to our [security documentation](docs/SECURITY.md)._

## License

This project is licensed under the **GPLv3 license**.

See [LICENSE](LICENSE.md) for more information.
