# WazuhTop

![Python](https://img.shields.io/badge/python-3.x-blue)
![Wazuh](https://img.shields.io/badge/wazuh-4.x-005571)
![License](https://img.shields.io/badge/license-MIT-green)

Interactive terminal alerts viewer for Wazuh — a port of [ossectop](https://github.com/meirm/ossectop) updated for modern Wazuh deployments. Watch live alerts in a `top`-style TUI directly on the manager.

**WazuhTop in action**

![WazuhTOP Overview](https://github.com/adampielak/wazuhtop/raw/main/screenshots/wazuhtop.jpeg)

## Quick start

```bash
git clone https://github.com/adampielak/wazuhtop.git
cd wazuhtop
python3 wazuhtop.py
```

Run on the Wazuh manager where `/var/ossec/logs/alerts/alerts.json` is present.

## Credits and Thank you

* [Meir Michanie OSSECTOP Author](https://github.com/meirm).
* Daniel Cid, who started the OSSEC project.
* [OSSEC core team members](http://ossec.github.io/about.html#ossec-team).
* [OSSEC developers and contributors](https://github.com/ossec/ossec-hids/blob/master/CONTRIBUTORS).
* [WAZUH core team members](https://wazuh.com/our-team/).
* [WAZUH developers and contributors](https://github.com/wazuh/wazuh/blob/master/CONTRIBUTORS).

Based on OSSECTOP

## References

* [Wazuh website](http://wazuh.com)
* [OSSEC project website](http://ossec.github.io)
