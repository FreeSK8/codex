---
layout: default
title: Home
nav_order: 1
description: "A technical documentation resource for the FreeSK8 Project & supported hardware & software."
permalink: /
---

# FreeSK8 Codex
{: .fs-9 }

A technical documenation resource for the FreeSK8 Project & supported hardware components.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Find us on GitHub](https://github.com/FreeSK8){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

### FreeSK8 Mobile

The Mobile application is a cross platform solution to monitor and configure [VESC](https://vesc-project.com/) based ESCs via Bluetooth. Learn all about it [here](./docs/freesk8-mobile/).

### FreeSK8 Robogotchi

The [FreeSK8 Robogotchi](https://derelictrobot.com/collections/production/products/freesk8-robogotchi) is an advanced BLE Receiver, Datalogger, and core component of the FreeSK8 System.

Think of it like a blackbox flight recorder for your esk8 or LEV. 

The Robogotchi brings Always-On Logging as a core feature with an asynchronous logging integration with our FreeSK8 Mobile App. 

Learn all about it [here](./docs/robogotchi/)

### FreeSK8 Remote (OSRR 1.0)

The [OSRR] Open Source Reconfigurable Remote is an open spec reference design for a robust remote control device for use with [VESC](https://vesc-project.com/) based PEVs.

Learn all about it [here](./docs/osrr/)

## About the project

FreeSK8 Codex is &copy; 2021 by [FreeSK8 Foundation NPO](http://freesk8.org).

### License

FreeSK8 Codex is distributed by a [GPL-3.0 license](https://github.com/DerelictRobot/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/DerelictRobot/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

FreeSK8 Foundation is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/DerelictRobot/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.