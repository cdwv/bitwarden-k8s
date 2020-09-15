# bitwarden-k8s
Helm chart for deploying [dani-garcia/bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs) in Kubernetes.

## TL;DR;

```console
$ helm repo add bitwarden https://cdwv.github.io/bitwarden-k8s/
$ helm install bitwarden/bitwarden-k8s
```

OR

```console
$ git clone https://github.com/cdwv/bitwarden-k8s
$ cd bitwarden-k8s
$ helm install ./chart/bitwarden-k8s
```


## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install --name my-release bitwarden/bitwarden-k8s
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## More info on Helm
Head over to [cdwv/awesome-helm](https://github.com/cdwv/awesome-helm) to learn more about Helm - the Kubernetes package manager.

License
=======================================================================

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" property="dct:title" rel="dct:type">bitwarden-k8s</span> by <a xmlns:cc="http://creativecommons.org" href="https://codewave.eu" property="cc:attributionName" rel="cc:attributionURL">CodeWave</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

Maintainers
===========

[<img width="300" title="Codewave.eu" src="cdwv-logo-new.svg">](http://codewave.eu)

Project is currently maintained, in our spare time, by [codewave.eu](http://codewave.eu) and a growing number of Contributors!
