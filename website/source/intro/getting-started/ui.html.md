---
layout: "intro"
page_title: "Web UI"
sidebar_current: "gettingstarted-ui"
description: |-
  Consul comes with support for beautiful, functional web UIs out of the box. UIs can be used for viewing all services and nodes, for viewing all health checks and their current status, and for reading and setting key/value data. The UIs automatically supports multi-datacenter.
---

# Consul Web UI

Consul comes with support for beautiful, functional web UIs out of the
box. UIs can be used for viewing all services and nodes, for viewing
all health checks and their current status, and for reading and setting
key/value data. The UIs automatically support multi-datacenter.

To set up the self-hosted UI, start the Consul agent with the
[`-ui` parameter](/docs/agent/options.html#_ui):

```text
$ consul agent -ui
...
```

The UI is available at the `/ui` path on the same port as the HTTP API.
By default this is `http://localhost:8500/ui`.

You can view a live demo of the Consul Web UI
[here](http://demo.consul.io).

## How to Use the New UI

On May 11, 2018, our redesign of the web UI went into beta. You can use it with
Consul 1.1.0 by setting the environment variable `CONSUL_UI_BETA` to `true`.
Without this environment variable, the web UI will default to the old version. To
use the old UI version, either set `CONSUL_UI_BETA` to false, or don't include
that environment variable at all.

## Next Steps

This concludes our Getting Started guide. See the
[next steps](next-steps.html) page to learn more about how to continue
your journey with Consul!
