# Cacti v1.2.24 authenticated command injection (CVE-TBD) vulnerable application

This is a vulnerable application to test the exploit for the **Cacti** vulnerability (**CVE-TBD**).

## WARNING!

**This application contains serious security vulnerabilities. Run it at your own risk! It is recommended using a backed-up and sheltered environment (such as a VM with a recent snapshot and host-only networking). Do not upload this application to any Internet facing servers, as they will be compromised.**

***DISCLAIMER*: I do not take responsibility for the way in which any one uses this application. The only purpose of this application is to be a test scenario for the CVE-TBD exploit and it should not be used maliciously. If your server is compromised via an installation of this application it is not my responsibility, it is the responsibility of the person(s) who uploaded and installed it.**

## Vulnerability info

* **CVE-ID**: CVE-TBD
* **Link**: [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-TBD](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-TBD)
* **Description**: TBD

## Usage

Here the steps to **setup** the environment:
1. Launch `docker compose up -d` to start composition.
2. You can finalize the steps by browsing to [http://127.0.0.1/cacti](http://127.0.0.1/cacti) to start the Cacti initialization wizard. If you get an error referring to the database, just wait a little bit and refresh the page.
3. Default credentials are `admin`/`admin`.
4. Press "*Next*" to all the buttons during the wizard, choosing options accordingly. All the defaults should be fine and all the mandatory prerequisites should be satisfied.
5. After the installation, TBD

The container will be called `vuln-cacti`.
The hostname for a test SNMP device is `monitored_snmp_device`.

To **teardown** the environment use `docker compose down` command.

The official installation guide of Cacti can be found [here](https://docs.cacti.net/README.md#cacti-installation).

## Root cause

A detailed root cause of the vulnerability is available in the [original security advisory]() or in [my blog post]().

## Exploit

TBD

## Authors

* **Antonio Francesco Sardella** - *vulnerability reporter* - [m3ssap0](https://github.com/m3ssap0)

## License

This project is licensed under the Unlicense - see the **LICENSE** file for details.
