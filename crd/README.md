# Pure Storage / Portworx Kubernetes CRDs

Custom Resource Definitions for Pure Storage's Kubernetes-native Portworx data services platform, sourced from `libopenstorage/operator` and `portworx/apis` GitHub repositories.

| Kind | Group | Versions | Scope | File |
|------|-------|----------|-------|------|
| StorageCluster | core.libopenstorage.org | v1, v1alpha1 | Namespaced | [pure-storage-portworx-storagecluster.yaml](pure-storage-portworx-storagecluster.yaml) |
| StorageNode | core.libopenstorage.org | v1, v1alpha1 | Namespaced | [pure-storage-portworx-storagenode.yaml](pure-storage-portworx-storagenode.yaml) |
| PortworxDiag | portworx.io | v1 | Namespaced | [pure-storage-portworx-portworxdiag.yaml](pure-storage-portworx-portworxdiag.yaml) |
| PortworxXcopyVolumePopulator | portworx.io | v1beta1 | Namespaced | [pure-storage-portworx-xcopyvolumepopulator.yaml](pure-storage-portworx-xcopyvolumepopulator.yaml) |

## Sources

- https://github.com/libopenstorage/operator/tree/master/deploy/crds
- https://github.com/portworx/apis/tree/master/config/crd

## Notes

- `StorageCluster` is the primary CRD that declaratively manages a Portworx storage cluster on Kubernetes.
- `StorageNode` represents the per-node Portworx storage runtime status.
- `PortworxDiag` triggers diagnostic data collection across the Portworx cluster.
- `PortworxXcopyVolumePopulator` enables FlashArray-accelerated XCOPY volume population for Kubernetes PersistentVolumes.
