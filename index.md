---
layout: default
title: Home
nav_order: 1
description: "A technical documentation resource for the FreeSK8 Project & supported hardware & software."
permalink: /
---

# FreeSK8 Codex
{: .fs-9 }

A technical documentation resource for the FreeSK8 Project & supported hardware components.
{: .fs-6 .fw-300 }

[Get FreeSK8 Mobile](https://freesk8.app){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Find us on GitHub](https://github.com/FreeSK8){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## [FreeSK8 Mobile](https://codex.freesk8.org/docs/freesk8-mobile/)

The [FreeSK8 Mobile](https://freesk8.app) application is a cross platform solution to monitor and configure [VESC](https://vesc-project.com/) based ESCs via Bluetooth. Learn all about it [here](./docs/freesk8-mobile/).

## [FreeSK8 Robogotchi](https://codex.freesk8.org/docs/robogotchi/)

The FreeSK8 Robogotchi is an advanced BLE Receiver, Datalogger, and core component of the FreeSK8 System.

The Robogotchi brings Always-On Logging as a core feature with an asynchronous logging integration with our FreeSK8 Mobile App. Think of it like a blackbox flight recorder for your esk8 or LEV. 

Learn all about it [here](./docs/robogotchi/)

## [FreeSK8 Remote (OSRR 1.0)](https://codex.freesk8.org/docs/osrr/)

The OSRR (Open Source Reconfigurable Remote) is an open spec reference design for a robust remote control device for use with [VESC](https://vesc-project.com/) based PEVs. 

Learn all about it [here](./docs/osrr/)

## [FreeSK8 netBMS](https://codex.freesk8.org/docs/bms/)

A connected, intelligent battery charge monitor system. More info coming soon.  

## [sk8net](https://codex.freesk8.org/docs/sk8net/)

sk8net with a lowercase 8 is a collection of online tools and connected services built to provide a useful data platform for personal electric vehicles.


## About the project

FreeSK8 Codex is &copy; 2021 by [FreeSK8 Foundation NPO](https://freesk8.org).

You can support this project on the [FreeSK8 Patreon](https://Patreon.com/FreeSK8Devs).

### License

FreeSK8 Codex is distributed by a [GPL-3.0 license](https://github.com/FreeSK8/codex/tree/master/LICENSE).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/FreeSK8/codex#contributing).

#### Thank you to the contributors of FreeSK8 Codex!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

FreeSK8 Foundation is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/FreeSK8/codex/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
