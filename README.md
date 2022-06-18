# Service Mesh Resources

## Exracts

Service mehses insert a proxy into each application pod, which intercepts and augments the TCP communication to and from the pod. These proxies run in their own containers alongside the application container, it's the the “sidecar” model.

Adapted from _eBPF, sidecars, and the future of the service mesh_.

## Bibliograhy

* Calçado, P. (2017, August 3). _Pattern: Service Mesh._ Phil Calçado. https://philcalcado.com/2017/08/03/pattern_service_mesh.html

* Bryant, D., & Humble, C. (2020, February 18). _Service Mesh Ultimate Guide: Managing Service-to-Service Communications in the Era of Microservices._ InfoQ. https://www.infoq.com/articles/service-mesh-ultimate-guide/

* Morgan, W. (2022, Jun 7). _eBPF, sidecars, and the future of the service mesh_ Buoyant. https://buoyant.io/2022/06/07/ebpf-sidecars-and-the-future-of-the-service-mesh/
