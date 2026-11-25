<p align="center"><img src="https://raw.githubusercontent.com/kubernanny/kubernanny/main/branding/kubernanny-icon-1024.png" alt="Kubernanny" width="112"></p>

<h3 align="center">Is my cluster okay, and if not, what exactly is wrong?</h3>

<p align="center">Health checks for self-hosted Kubernetes, on your phone and in the browser.</p>

Kubernanny is a small agent for your cluster plus an app for iOS, Android and the web. The agent recognises what you run (Longhorn, Argo CD, cert-manager, CloudNativePG, Prometheus, Loki, kured and about 70 more) and checks each of them the way you would by hand. The app shows one light per cluster and, below it, only what is broken right now, why, and the action that usually fixes it.

- **Read-only by default.** Actions such as restarting a broken workload are opt-in, bound to an open issue and switchable per cluster.
- **End-to-end encrypted.** The phone talks to the agent through a Noise protocol; the optional relay only forwards sealed bytes.
- **Built-in standard alerts.** etcd peer latency, filesystem and volume fill forecasts, overcommit and the rest of the community alert sets, without writing Prometheus rules.
- **Free and open source** under the Apache 2.0 licence.

👉 Start with the [kubernanny repository](https://github.com/kubernanny/kubernanny): install in one Helm command, or try the recorded demo cluster first.
