https://github.com/kubernetes-client/java/tree/master/kubernetes/docs

> https://github.com/kubernetes-client/java/blob/master/kubernetes/docs/CoreV1Api.md



# CoreV1Api

All URIs are relative to *https://localhost*

| Method                                                       | HTTP request                                                 | Description |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- |
| [**connectDeleteNamespacedPodProxy**](CoreV1Api.md#connectDeleteNamespacedPodProxy) | **DELETE** /api/v1/namespaces/{namespace}/pods/{name}/proxy  |             |
| [**connectDeleteNamespacedPodProxyWithPath**](CoreV1Api.md#connectDeleteNamespacedPodProxyWithPath) | **DELETE** /api/v1/namespaces/{namespace}/pods/{name}/proxy/{path} |             |
| [**connectDeleteNamespacedServiceProxy**](CoreV1Api.md#connectDeleteNamespacedServiceProxy) | **DELETE** /api/v1/namespaces/{namespace}/services/{name}/proxy |             |
| [**connectDeleteNamespacedServiceProxyWithPath**](CoreV1Api.md#connectDeleteNamespacedServiceProxyWithPath) | **DELETE** /api/v1/namespaces/{namespace}/services/{name}/proxy/{path} |             |
| [**connectDeleteNodeProxy**](CoreV1Api.md#connectDeleteNodeProxy) | **DELETE** /api/v1/nodes/{name}/proxy                        |             |
| [**connectDeleteNodeProxyWithPath**](CoreV1Api.md#connectDeleteNodeProxyWithPath) | **DELETE** /api/v1/nodes/{name}/proxy/{path}                 |             |
| [**connectGetNamespacedPodAttach**](CoreV1Api.md#connectGetNamespacedPodAttach) | **GET** /api/v1/namespaces/{namespace}/pods/{name}/attach    |             |
| [**connectGetNamespacedPodExec**](CoreV1Api.md#connectGetNamespacedPodExec) | **GET** /api/v1/namespaces/{namespace}/pods/{name}/exec      |             |
| [**connectGetNamespacedPodPortforward**](CoreV1Api.md#connectGetNamespacedPodPortforward) | **GET** /api/v1/namespaces/{namespace}/pods/{name}/portforward |             |
| [**connectGetNamespacedPodProxy**](CoreV1Api.md#connectGetNamespacedPodProxy) | **GET** /api/v1/namespaces/{namespace}/pods/{name}/proxy     |             |
| [**connectGetNamespacedPodProxyWithPath**](CoreV1Api.md#connectGetNamespacedPodProxyWithPath) | **GET** /api/v1/namespaces/{namespace}/pods/{name}/proxy/{path} |             |
| [**connectGetNamespacedServiceProxy**](CoreV1Api.md#connectGetNamespacedServiceProxy) | **GET** /api/v1/namespaces/{namespace}/services/{name}/proxy |             |
| [**connectGetNamespacedServiceProxyWithPath**](CoreV1Api.md#connectGetNamespacedServiceProxyWithPath) | **GET** /api/v1/namespaces/{namespace}/services/{name}/proxy/{path} |             |
| [**connectGetNodeProxy**](CoreV1Api.md#connectGetNodeProxy)  | **GET** /api/v1/nodes/{name}/proxy                           |             |
| [**connectGetNodeProxyWithPath**](CoreV1Api.md#connectGetNodeProxyWithPath) | **GET** /api/v1/nodes/{name}/proxy/{path}                    |             |
| [**connectHeadNamespacedPodProxy**](CoreV1Api.md#connectHeadNamespacedPodProxy) | **HEAD** /api/v1/namespaces/{namespace}/pods/{name}/proxy    |             |
| [**connectHeadNamespacedPodProxyWithPath**](CoreV1Api.md#connectHeadNamespacedPodProxyWithPath) | **HEAD** /api/v1/namespaces/{namespace}/pods/{name}/proxy/{path} |             |
| [**connectHeadNamespacedServiceProxy**](CoreV1Api.md#connectHeadNamespacedServiceProxy) | **HEAD** /api/v1/namespaces/{namespace}/services/{name}/proxy |             |
| [**connectHeadNamespacedServiceProxyWithPath**](CoreV1Api.md#connectHeadNamespacedServiceProxyWithPath) | **HEAD** /api/v1/namespaces/{namespace}/services/{name}/proxy/{path} |             |
| [**connectHeadNodeProxy**](CoreV1Api.md#connectHeadNodeProxy) | **HEAD** /api/v1/nodes/{name}/proxy                          |             |
| [**connectHeadNodeProxyWithPath**](CoreV1Api.md#connectHeadNodeProxyWithPath) | **HEAD** /api/v1/nodes/{name}/proxy/{path}                   |             |
| [**connectOptionsNamespacedPodProxy**](CoreV1Api.md#connectOptionsNamespacedPodProxy) | **OPTIONS** /api/v1/namespaces/{namespace}/pods/{name}/proxy |             |
| [**connectOptionsNamespacedPodProxyWithPath**](CoreV1Api.md#connectOptionsNamespacedPodProxyWithPath) | **OPTIONS** /api/v1/namespaces/{namespace}/pods/{name}/proxy/{path} |             |
| [**connectOptionsNamespacedServiceProxy**](CoreV1Api.md#connectOptionsNamespacedServiceProxy) | **OPTIONS** /api/v1/namespaces/{namespace}/services/{name}/proxy |             |
| [**connectOptionsNamespacedServiceProxyWithPath**](CoreV1Api.md#connectOptionsNamespacedServiceProxyWithPath) | **OPTIONS** /api/v1/namespaces/{namespace}/services/{name}/proxy/{path} |             |
| [**connectOptionsNodeProxy**](CoreV1Api.md#connectOptionsNodeProxy) | **OPTIONS** /api/v1/nodes/{name}/proxy                       |             |
| [**connectOptionsNodeProxyWithPath**](CoreV1Api.md#connectOptionsNodeProxyWithPath) | **OPTIONS** /api/v1/nodes/{name}/proxy/{path}                |             |
| [**connectPatchNamespacedPodProxy**](CoreV1Api.md#connectPatchNamespacedPodProxy) | **PATCH** /api/v1/namespaces/{namespace}/pods/{name}/proxy   |             |
| [**connectPatchNamespacedPodProxyWithPath**](CoreV1Api.md#connectPatchNamespacedPodProxyWithPath) | **PATCH** /api/v1/namespaces/{namespace}/pods/{name}/proxy/{path} |             |
| [**connectPatchNamespacedServiceProxy**](CoreV1Api.md#connectPatchNamespacedServiceProxy) | **PATCH** /api/v1/namespaces/{namespace}/services/{name}/proxy |             |
| [**connectPatchNamespacedServiceProxyWithPath**](CoreV1Api.md#connectPatchNamespacedServiceProxyWithPath) | **PATCH** /api/v1/namespaces/{namespace}/services/{name}/proxy/{path} |             |
| [**connectPatchNodeProxy**](CoreV1Api.md#connectPatchNodeProxy) | **PATCH** /api/v1/nodes/{name}/proxy                         |             |
| [**connectPatchNodeProxyWithPath**](CoreV1Api.md#connectPatchNodeProxyWithPath) | **PATCH** /api/v1/nodes/{name}/proxy/{path}                  |             |
| [**connectPostNamespacedPodAttach**](CoreV1Api.md#connectPostNamespacedPodAttach) | **POST** /api/v1/namespaces/{namespace}/pods/{name}/attach   |             |
| [**connectPostNamespacedPodExec**](CoreV1Api.md#connectPostNamespacedPodExec) | **POST** /api/v1/namespaces/{namespace}/pods/{name}/exec     |             |
| [**connectPostNamespacedPodPortforward**](CoreV1Api.md#connectPostNamespacedPodPortforward) | **POST** /api/v1/namespaces/{namespace}/pods/{name}/portforward |             |
| [**connectPostNamespacedPodProxy**](CoreV1Api.md#connectPostNamespacedPodProxy) | **POST** /api/v1/namespaces/{namespace}/pods/{name}/proxy    |             |
| [**connectPostNamespacedPodProxyWithPath**](CoreV1Api.md#connectPostNamespacedPodProxyWithPath) | **POST** /api/v1/namespaces/{namespace}/pods/{name}/proxy/{path} |             |
| [**connectPostNamespacedServiceProxy**](CoreV1Api.md#connectPostNamespacedServiceProxy) | **POST** /api/v1/namespaces/{namespace}/services/{name}/proxy |             |
| [**connectPostNamespacedServiceProxyWithPath**](CoreV1Api.md#connectPostNamespacedServiceProxyWithPath) | **POST** /api/v1/namespaces/{namespace}/services/{name}/proxy/{path} |             |
| [**connectPostNodeProxy**](CoreV1Api.md#connectPostNodeProxy) | **POST** /api/v1/nodes/{name}/proxy                          |             |
| [**connectPostNodeProxyWithPath**](CoreV1Api.md#connectPostNodeProxyWithPath) | **POST** /api/v1/nodes/{name}/proxy/{path}                   |             |
| [**connectPutNamespacedPodProxy**](CoreV1Api.md#connectPutNamespacedPodProxy) | **PUT** /api/v1/namespaces/{namespace}/pods/{name}/proxy     |             |
| [**connectPutNamespacedPodProxyWithPath**](CoreV1Api.md#connectPutNamespacedPodProxyWithPath) | **PUT** /api/v1/namespaces/{namespace}/pods/{name}/proxy/{path} |             |
| [**connectPutNamespacedServiceProxy**](CoreV1Api.md#connectPutNamespacedServiceProxy) | **PUT** /api/v1/namespaces/{namespace}/services/{name}/proxy |             |
| [**connectPutNamespacedServiceProxyWithPath**](CoreV1Api.md#connectPutNamespacedServiceProxyWithPath) | **PUT** /api/v1/namespaces/{namespace}/services/{name}/proxy/{path} |             |
| [**connectPutNodeProxy**](CoreV1Api.md#connectPutNodeProxy)  | **PUT** /api/v1/nodes/{name}/proxy                           |             |
| [**connectPutNodeProxyWithPath**](CoreV1Api.md#connectPutNodeProxyWithPath) | **PUT** /api/v1/nodes/{name}/proxy/{path}                    |             |
| [**createNamespace**](CoreV1Api.md#createNamespace)          | **POST** /api/v1/namespaces                                  |             |
| [**createNamespacedBinding**](CoreV1Api.md#createNamespacedBinding) | **POST** /api/v1/namespaces/{namespace}/bindings             |             |
| [**createNamespacedConfigMap**](CoreV1Api.md#createNamespacedConfigMap) | **POST** /api/v1/namespaces/{namespace}/configmaps           |             |
| [**createNamespacedEndpoints**](CoreV1Api.md#createNamespacedEndpoints) | **POST** /api/v1/namespaces/{namespace}/endpoints            |             |
| [**createNamespacedEvent**](CoreV1Api.md#createNamespacedEvent) | **POST** /api/v1/namespaces/{namespace}/events               |             |
| [**createNamespacedLimitRange**](CoreV1Api.md#createNamespacedLimitRange) | **POST** /api/v1/namespaces/{namespace}/limitranges          |             |
| [**createNamespacedPersistentVolumeClaim**](CoreV1Api.md#createNamespacedPersistentVolumeClaim) | **POST** /api/v1/namespaces/{namespace}/persistentvolumeclaims |             |
| [**createNamespacedPod**](CoreV1Api.md#createNamespacedPod)  | **POST** /api/v1/namespaces/{namespace}/pods                 |             |
| [**createNamespacedPodBinding**](CoreV1Api.md#createNamespacedPodBinding) | **POST** /api/v1/namespaces/{namespace}/pods/{name}/binding  |             |
| [**createNamespacedPodEviction**](CoreV1Api.md#createNamespacedPodEviction) | **POST** /api/v1/namespaces/{namespace}/pods/{name}/eviction |             |
| [**createNamespacedPodTemplate**](CoreV1Api.md#createNamespacedPodTemplate) | **POST** /api/v1/namespaces/{namespace}/podtemplates         |             |
| [**createNamespacedReplicationController**](CoreV1Api.md#createNamespacedReplicationController) | **POST** /api/v1/namespaces/{namespace}/replicationcontrollers |             |
| [**createNamespacedResourceQuota**](CoreV1Api.md#createNamespacedResourceQuota) | **POST** /api/v1/namespaces/{namespace}/resourcequotas       |             |
| [**createNamespacedSecret**](CoreV1Api.md#createNamespacedSecret) | **POST** /api/v1/namespaces/{namespace}/secrets              |             |
| [**createNamespacedService**](CoreV1Api.md#createNamespacedService) | **POST** /api/v1/namespaces/{namespace}/services             |             |
| [**createNamespacedServiceAccount**](CoreV1Api.md#createNamespacedServiceAccount) | **POST** /api/v1/namespaces/{namespace}/serviceaccounts      |             |
| [**createNode**](CoreV1Api.md#createNode)                    | **POST** /api/v1/nodes                                       |             |
| [**createPersistentVolume**](CoreV1Api.md#createPersistentVolume) | **POST** /api/v1/persistentvolumes                           |             |
| [**deleteCollectionNamespacedConfigMap**](CoreV1Api.md#deleteCollectionNamespacedConfigMap) | **DELETE** /api/v1/namespaces/{namespace}/configmaps         |             |
| [**deleteCollectionNamespacedEndpoints**](CoreV1Api.md#deleteCollectionNamespacedEndpoints) | **DELETE** /api/v1/namespaces/{namespace}/endpoints          |             |
| [**deleteCollectionNamespacedEvent**](CoreV1Api.md#deleteCollectionNamespacedEvent) | **DELETE** /api/v1/namespaces/{namespace}/events             |             |
| [**deleteCollectionNamespacedLimitRange**](CoreV1Api.md#deleteCollectionNamespacedLimitRange) | **DELETE** /api/v1/namespaces/{namespace}/limitranges        |             |
| [**deleteCollectionNamespacedPersistentVolumeClaim**](CoreV1Api.md#deleteCollectionNamespacedPersistentVolumeClaim) | **DELETE** /api/v1/namespaces/{namespace}/persistentvolumeclaims |             |
| [**deleteCollectionNamespacedPod**](CoreV1Api.md#deleteCollectionNamespacedPod) | **DELETE** /api/v1/namespaces/{namespace}/pods               |             |
| [**deleteCollectionNamespacedPodTemplate**](CoreV1Api.md#deleteCollectionNamespacedPodTemplate) | **DELETE** /api/v1/namespaces/{namespace}/podtemplates       |             |
| [**deleteCollectionNamespacedReplicationController**](CoreV1Api.md#deleteCollectionNamespacedReplicationController) | **DELETE** /api/v1/namespaces/{namespace}/replicationcontrollers |             |
| [**deleteCollectionNamespacedResourceQuota**](CoreV1Api.md#deleteCollectionNamespacedResourceQuota) | **DELETE** /api/v1/namespaces/{namespace}/resourcequotas     |             |
| [**deleteCollectionNamespacedSecret**](CoreV1Api.md#deleteCollectionNamespacedSecret) | **DELETE** /api/v1/namespaces/{namespace}/secrets            |             |
| [**deleteCollectionNamespacedServiceAccount**](CoreV1Api.md#deleteCollectionNamespacedServiceAccount) | **DELETE** /api/v1/namespaces/{namespace}/serviceaccounts    |             |
| [**deleteCollectionNode**](CoreV1Api.md#deleteCollectionNode) | **DELETE** /api/v1/nodes                                     |             |
| [**deleteCollectionPersistentVolume**](CoreV1Api.md#deleteCollectionPersistentVolume) | **DELETE** /api/v1/persistentvolumes                         |             |
| [**deleteNamespace**](CoreV1Api.md#deleteNamespace)          | **DELETE** /api/v1/namespaces/{name}                         |             |
| [**deleteNamespacedConfigMap**](CoreV1Api.md#deleteNamespacedConfigMap) | **DELETE** /api/v1/namespaces/{namespace}/configmaps/{name}  |             |
| [**deleteNamespacedEndpoints**](CoreV1Api.md#deleteNamespacedEndpoints) | **DELETE** /api/v1/namespaces/{namespace}/endpoints/{name}   |             |
| [**deleteNamespacedEvent**](CoreV1Api.md#deleteNamespacedEvent) | **DELETE** /api/v1/namespaces/{namespace}/events/{name}      |             |
| [**deleteNamespacedLimitRange**](CoreV1Api.md#deleteNamespacedLimitRange) | **DELETE** /api/v1/namespaces/{namespace}/limitranges/{name} |             |
| [**deleteNamespacedPersistentVolumeClaim**](CoreV1Api.md#deleteNamespacedPersistentVolumeClaim) | **DELETE** /api/v1/namespaces/{namespace}/persistentvolumeclaims/{name} |             |
| [**deleteNamespacedPod**](CoreV1Api.md#deleteNamespacedPod)  | **DELETE** /api/v1/namespaces/{namespace}/pods/{name}        |             |
| [**deleteNamespacedPodTemplate**](CoreV1Api.md#deleteNamespacedPodTemplate) | **DELETE** /api/v1/namespaces/{namespace}/podtemplates/{name} |             |
| [**deleteNamespacedReplicationController**](CoreV1Api.md#deleteNamespacedReplicationController) | **DELETE** /api/v1/namespaces/{namespace}/replicationcontrollers/{name} |             |
| [**deleteNamespacedResourceQuota**](CoreV1Api.md#deleteNamespacedResourceQuota) | **DELETE** /api/v1/namespaces/{namespace}/resourcequotas/{name} |             |
| [**deleteNamespacedSecret**](CoreV1Api.md#deleteNamespacedSecret) | **DELETE** /api/v1/namespaces/{namespace}/secrets/{name}     |             |
| [**deleteNamespacedService**](CoreV1Api.md#deleteNamespacedService) | **DELETE** /api/v1/namespaces/{namespace}/services/{name}    |             |
| [**deleteNamespacedServiceAccount**](CoreV1Api.md#deleteNamespacedServiceAccount) | **DELETE** /api/v1/namespaces/{namespace}/serviceaccounts/{name} |             |
| [**deleteNode**](CoreV1Api.md#deleteNode)                    | **DELETE** /api/v1/nodes/{name}                              |             |
| [**deletePersistentVolume**](CoreV1Api.md#deletePersistentVolume) | **DELETE** /api/v1/persistentvolumes/{name}                  |             |
| [**getAPIResources**](CoreV1Api.md#getAPIResources)          | **GET** /api/v1/                                             |             |
| [**listComponentStatus**](CoreV1Api.md#listComponentStatus)  | **GET** /api/v1/componentstatuses                            |             |
| [**listConfigMapForAllNamespaces**](CoreV1Api.md#listConfigMapForAllNamespaces) | **GET** /api/v1/configmaps                                   |             |
| [**listEndpointsForAllNamespaces**](CoreV1Api.md#listEndpointsForAllNamespaces) | **GET** /api/v1/endpoints                                    |             |
| [**listEventForAllNamespaces**](CoreV1Api.md#listEventForAllNamespaces) | **GET** /api/v1/events                                       |             |
| [**listLimitRangeForAllNamespaces**](CoreV1Api.md#listLimitRangeForAllNamespaces) | **GET** /api/v1/limitranges                                  |             |
| [**listNamespace**](CoreV1Api.md#listNamespace)              | **GET** /api/v1/namespaces                                   |             |
| [**listNamespacedConfigMap**](CoreV1Api.md#listNamespacedConfigMap) | **GET** /api/v1/namespaces/{namespace}/configmaps            |             |
| [**listNamespacedEndpoints**](CoreV1Api.md#listNamespacedEndpoints) | **GET** /api/v1/namespaces/{namespace}/endpoints             |             |
| [**listNamespacedEvent**](CoreV1Api.md#listNamespacedEvent)  | **GET** /api/v1/namespaces/{namespace}/events                |             |
| [**listNamespacedLimitRange**](CoreV1Api.md#listNamespacedLimitRange) | **GET** /api/v1/namespaces/{namespace}/limitranges           |             |
| [**listNamespacedPersistentVolumeClaim**](CoreV1Api.md#listNamespacedPersistentVolumeClaim) | **GET** /api/v1/namespaces/{namespace}/persistentvolumeclaims |             |
| [**listNamespacedPod**](CoreV1Api.md#listNamespacedPod)      | **GET** /api/v1/namespaces/{namespace}/pods                  |             |
| [**listNamespacedPodTemplate**](CoreV1Api.md#listNamespacedPodTemplate) | **GET** /api/v1/namespaces/{namespace}/podtemplates          |             |
| [**listNamespacedReplicationController**](CoreV1Api.md#listNamespacedReplicationController) | **GET** /api/v1/namespaces/{namespace}/replicationcontrollers |             |
| [**listNamespacedResourceQuota**](CoreV1Api.md#listNamespacedResourceQuota) | **GET** /api/v1/namespaces/{namespace}/resourcequotas        |             |
| [**listNamespacedSecret**](CoreV1Api.md#listNamespacedSecret) | **GET** /api/v1/namespaces/{namespace}/secrets               |             |
| [**listNamespacedService**](CoreV1Api.md#listNamespacedService) | **GET** /api/v1/namespaces/{namespace}/services              |             |
| [**listNamespacedServiceAccount**](CoreV1Api.md#listNamespacedServiceAccount) | **GET** /api/v1/namespaces/{namespace}/serviceaccounts       |             |
| [**listNode**](CoreV1Api.md#listNode)                        | **GET** /api/v1/nodes                                        |             |
| [**listPersistentVolume**](CoreV1Api.md#listPersistentVolume) | **GET** /api/v1/persistentvolumes                            |             |
| [**listPersistentVolumeClaimForAllNamespaces**](CoreV1Api.md#listPersistentVolumeClaimForAllNamespaces) | **GET** /api/v1/persistentvolumeclaims                       |             |
| [**listPodForAllNamespaces**](CoreV1Api.md#listPodForAllNamespaces) | **GET** /api/v1/pods                                         |             |
| [**listPodTemplateForAllNamespaces**](CoreV1Api.md#listPodTemplateForAllNamespaces) | **GET** /api/v1/podtemplates                                 |             |
| [**listReplicationControllerForAllNamespaces**](CoreV1Api.md#listReplicationControllerForAllNamespaces) | **GET** /api/v1/replicationcontrollers                       |             |
| [**listResourceQuotaForAllNamespaces**](CoreV1Api.md#listResourceQuotaForAllNamespaces) | **GET** /api/v1/resourcequotas                               |             |
| [**listSecretForAllNamespaces**](CoreV1Api.md#listSecretForAllNamespaces) | **GET** /api/v1/secrets                                      |             |
| [**listServiceAccountForAllNamespaces**](CoreV1Api.md#listServiceAccountForAllNamespaces) | **GET** /api/v1/serviceaccounts                              |             |
| [**listServiceForAllNamespaces**](CoreV1Api.md#listServiceForAllNamespaces) | **GET** /api/v1/services                                     |             |
| [**patchNamespace**](CoreV1Api.md#patchNamespace)            | **PATCH** /api/v1/namespaces/{name}                          |             |
| [**patchNamespaceStatus**](CoreV1Api.md#patchNamespaceStatus) | **PATCH** /api/v1/namespaces/{name}/status                   |             |
| [**patchNamespacedConfigMap**](CoreV1Api.md#patchNamespacedConfigMap) | **PATCH** /api/v1/namespaces/{namespace}/configmaps/{name}   |             |
| [**patchNamespacedEndpoints**](CoreV1Api.md#patchNamespacedEndpoints) | **PATCH** /api/v1/namespaces/{namespace}/endpoints/{name}    |             |
| [**patchNamespacedEvent**](CoreV1Api.md#patchNamespacedEvent) | **PATCH** /api/v1/namespaces/{namespace}/events/{name}       |             |
| [**patchNamespacedLimitRange**](CoreV1Api.md#patchNamespacedLimitRange) | **PATCH** /api/v1/namespaces/{namespace}/limitranges/{name}  |             |
| [**patchNamespacedPersistentVolumeClaim**](CoreV1Api.md#patchNamespacedPersistentVolumeClaim) | **PATCH** /api/v1/namespaces/{namespace}/persistentvolumeclaims/{name} |             |
| [**patchNamespacedPersistentVolumeClaimStatus**](CoreV1Api.md#patchNamespacedPersistentVolumeClaimStatus) | **PATCH** /api/v1/namespaces/{namespace}/persistentvolumeclaims/{name}/status |             |
| [**patchNamespacedPod**](CoreV1Api.md#patchNamespacedPod)    | **PATCH** /api/v1/namespaces/{namespace}/pods/{name}         |             |
| [**patchNamespacedPodStatus**](CoreV1Api.md#patchNamespacedPodStatus) | **PATCH** /api/v1/namespaces/{namespace}/pods/{name}/status  |             |
| [**patchNamespacedPodTemplate**](CoreV1Api.md#patchNamespacedPodTemplate) | **PATCH** /api/v1/namespaces/{namespace}/podtemplates/{name} |             |
| [**patchNamespacedReplicationController**](CoreV1Api.md#patchNamespacedReplicationController) | **PATCH** /api/v1/namespaces/{namespace}/replicationcontrollers/{name} |             |
| [**patchNamespacedReplicationControllerScale**](CoreV1Api.md#patchNamespacedReplicationControllerScale) | **PATCH** /api/v1/namespaces/{namespace}/replicationcontrollers/{name}/scale |             |
| [**patchNamespacedReplicationControllerStatus**](CoreV1Api.md#patchNamespacedReplicationControllerStatus) | **PATCH** /api/v1/namespaces/{namespace}/replicationcontrollers/{name}/status |             |
| [**patchNamespacedResourceQuota**](CoreV1Api.md#patchNamespacedResourceQuota) | **PATCH** /api/v1/namespaces/{namespace}/resourcequotas/{name} |             |
| [**patchNamespacedResourceQuotaStatus**](CoreV1Api.md#patchNamespacedResourceQuotaStatus) | **PATCH** /api/v1/namespaces/{namespace}/resourcequotas/{name}/status |             |
| [**patchNamespacedSecret**](CoreV1Api.md#patchNamespacedSecret) | **PATCH** /api/v1/namespaces/{namespace}/secrets/{name}      |             |
| [**patchNamespacedService**](CoreV1Api.md#patchNamespacedService) | **PATCH** /api/v1/namespaces/{namespace}/services/{name}     |             |
| [**patchNamespacedServiceAccount**](CoreV1Api.md#patchNamespacedServiceAccount) | **PATCH** /api/v1/namespaces/{namespace}/serviceaccounts/{name} |             |
| [**patchNamespacedServiceStatus**](CoreV1Api.md#patchNamespacedServiceStatus) | **PATCH** /api/v1/namespaces/{namespace}/services/{name}/status |             |
| [**patchNode**](CoreV1Api.md#patchNode)                      | **PATCH** /api/v1/nodes/{name}                               |             |
| [**patchNodeStatus**](CoreV1Api.md#patchNodeStatus)          | **PATCH** /api/v1/nodes/{name}/status                        |             |
| [**patchPersistentVolume**](CoreV1Api.md#patchPersistentVolume) | **PATCH** /api/v1/persistentvolumes/{name}                   |             |
| [**patchPersistentVolumeStatus**](CoreV1Api.md#patchPersistentVolumeStatus) | **PATCH** /api/v1/persistentvolumes/{name}/status            |             |
| [**readComponentStatus**](CoreV1Api.md#readComponentStatus)  | **GET** /api/v1/componentstatuses/{name}                     |             |
| [**readNamespace**](CoreV1Api.md#readNamespace)              | **GET** /api/v1/namespaces/{name}                            |             |
| [**readNamespaceStatus**](CoreV1Api.md#readNamespaceStatus)  | **GET** /api/v1/namespaces/{name}/status                     |             |
| [**readNamespacedConfigMap**](CoreV1Api.md#readNamespacedConfigMap) | **GET** /api/v1/namespaces/{namespace}/configmaps/{name}     |             |
| [**readNamespacedEndpoints**](CoreV1Api.md#readNamespacedEndpoints) | **GET** /api/v1/namespaces/{namespace}/endpoints/{name}      |             |
| [**readNamespacedEvent**](CoreV1Api.md#readNamespacedEvent)  | **GET** /api/v1/namespaces/{namespace}/events/{name}         |             |
| [**readNamespacedLimitRange**](CoreV1Api.md#readNamespacedLimitRange) | **GET** /api/v1/namespaces/{namespace}/limitranges/{name}    |             |
| [**readNamespacedPersistentVolumeClaim**](CoreV1Api.md#readNamespacedPersistentVolumeClaim) | **GET** /api/v1/namespaces/{namespace}/persistentvolumeclaims/{name} |             |
| [**readNamespacedPersistentVolumeClaimStatus**](CoreV1Api.md#readNamespacedPersistentVolumeClaimStatus) | **GET** /api/v1/namespaces/{namespace}/persistentvolumeclaims/{name}/status |             |
| [**readNamespacedPod**](CoreV1Api.md#readNamespacedPod)      | **GET** /api/v1/namespaces/{namespace}/pods/{name}           |             |
| [**readNamespacedPodLog**](CoreV1Api.md#readNamespacedPodLog) | **GET** /api/v1/namespaces/{namespace}/pods/{name}/log       |             |
| [**readNamespacedPodStatus**](CoreV1Api.md#readNamespacedPodStatus) | **GET** /api/v1/namespaces/{namespace}/pods/{name}/status    |             |
| [**readNamespacedPodTemplate**](CoreV1Api.md#readNamespacedPodTemplate) | **GET** /api/v1/namespaces/{namespace}/podtemplates/{name}   |             |
| [**readNamespacedReplicationController**](CoreV1Api.md#readNamespacedReplicationController) | **GET** /api/v1/namespaces/{namespace}/replicationcontrollers/{name} |             |
| [**readNamespacedReplicationControllerScale**](CoreV1Api.md#readNamespacedReplicationControllerScale) | **GET** /api/v1/namespaces/{namespace}/replicationcontrollers/{name}/scale |             |
| [**readNamespacedReplicationControllerStatus**](CoreV1Api.md#readNamespacedReplicationControllerStatus) | **GET** /api/v1/namespaces/{namespace}/replicationcontrollers/{name}/status |             |
| [**readNamespacedResourceQuota**](CoreV1Api.md#readNamespacedResourceQuota) | **GET** /api/v1/namespaces/{namespace}/resourcequotas/{name} |             |
| [**readNamespacedResourceQuotaStatus**](CoreV1Api.md#readNamespacedResourceQuotaStatus) | **GET** /api/v1/namespaces/{namespace}/resourcequotas/{name}/status |             |
| [**readNamespacedSecret**](CoreV1Api.md#readNamespacedSecret) | **GET** /api/v1/namespaces/{namespace}/secrets/{name}        |             |
| [**readNamespacedService**](CoreV1Api.md#readNamespacedService) | **GET** /api/v1/namespaces/{namespace}/services/{name}       |             |
| [**readNamespacedServiceAccount**](CoreV1Api.md#readNamespacedServiceAccount) | **GET** /api/v1/namespaces/{namespace}/serviceaccounts/{name} |             |
| [**readNamespacedServiceStatus**](CoreV1Api.md#readNamespacedServiceStatus) | **GET** /api/v1/namespaces/{namespace}/services/{name}/status |             |
| [**readNode**](CoreV1Api.md#readNode)                        | **GET** /api/v1/nodes/{name}                                 |             |
| [**readNodeStatus**](CoreV1Api.md#readNodeStatus)            | **GET** /api/v1/nodes/{name}/status                          |             |
| [**readPersistentVolume**](CoreV1Api.md#readPersistentVolume) | **GET** /api/v1/persistentvolumes/{name}                     |             |
| [**readPersistentVolumeStatus**](CoreV1Api.md#readPersistentVolumeStatus) | **GET** /api/v1/persistentvolumes/{name}/status              |             |
| [**replaceNamespace**](CoreV1Api.md#replaceNamespace)        | **PUT** /api/v1/namespaces/{name}                            |             |
| [**replaceNamespaceFinalize**](CoreV1Api.md#replaceNamespaceFinalize) | **PUT** /api/v1/namespaces/{name}/finalize                   |             |
| [**replaceNamespaceStatus**](CoreV1Api.md#replaceNamespaceStatus) | **PUT** /api/v1/namespaces/{name}/status                     |             |
| [**replaceNamespacedConfigMap**](CoreV1Api.md#replaceNamespacedConfigMap) | **PUT** /api/v1/namespaces/{namespace}/configmaps/{name}     |             |
| [**replaceNamespacedEndpoints**](CoreV1Api.md#replaceNamespacedEndpoints) | **PUT** /api/v1/namespaces/{namespace}/endpoints/{name}      |             |
| [**replaceNamespacedEvent**](CoreV1Api.md#replaceNamespacedEvent) | **PUT** /api/v1/namespaces/{namespace}/events/{name}         |             |
| [**replaceNamespacedLimitRange**](CoreV1Api.md#replaceNamespacedLimitRange) | **PUT** /api/v1/namespaces/{namespace}/limitranges/{name}    |             |
| [**replaceNamespacedPersistentVolumeClaim**](CoreV1Api.md#replaceNamespacedPersistentVolumeClaim) | **PUT** /api/v1/namespaces/{namespace}/persistentvolumeclaims/{name} |             |
| [**replaceNamespacedPersistentVolumeClaimStatus**](CoreV1Api.md#replaceNamespacedPersistentVolumeClaimStatus) | **PUT** /api/v1/namespaces/{namespace}/persistentvolumeclaims/{name}/status |             |
| [**replaceNamespacedPod**](CoreV1Api.md#replaceNamespacedPod) | **PUT** /api/v1/namespaces/{namespace}/pods/{name}           |             |
| [**replaceNamespacedPodStatus**](CoreV1Api.md#replaceNamespacedPodStatus) | **PUT** /api/v1/namespaces/{namespace}/pods/{name}/status    |             |
| [**replaceNamespacedPodTemplate**](CoreV1Api.md#replaceNamespacedPodTemplate) | **PUT** /api/v1/namespaces/{namespace}/podtemplates/{name}   |             |
| [**replaceNamespacedReplicationController**](CoreV1Api.md#replaceNamespacedReplicationController) | **PUT** /api/v1/namespaces/{namespace}/replicationcontrollers/{name} |             |
| [**replaceNamespacedReplicationControllerScale**](CoreV1Api.md#replaceNamespacedReplicationControllerScale) | **PUT** /api/v1/namespaces/{namespace}/replicationcontrollers/{name}/scale |             |
| [**replaceNamespacedReplicationControllerStatus**](CoreV1Api.md#replaceNamespacedReplicationControllerStatus) | **PUT** /api/v1/namespaces/{namespace}/replicationcontrollers/{name}/status |             |
| [**replaceNamespacedResourceQuota**](CoreV1Api.md#replaceNamespacedResourceQuota) | **PUT** /api/v1/namespaces/{namespace}/resourcequotas/{name} |             |
| [**replaceNamespacedResourceQuotaStatus**](CoreV1Api.md#replaceNamespacedResourceQuotaStatus) | **PUT** /api/v1/namespaces/{namespace}/resourcequotas/{name}/status |             |
| [**replaceNamespacedSecret**](CoreV1Api.md#replaceNamespacedSecret) | **PUT** /api/v1/namespaces/{namespace}/secrets/{name}        |             |
| [**replaceNamespacedService**](CoreV1Api.md#replaceNamespacedService) | **PUT** /api/v1/namespaces/{namespace}/services/{name}       |             |
| [**replaceNamespacedServiceAccount**](CoreV1Api.md#replaceNamespacedServiceAccount) | **PUT** /api/v1/namespaces/{namespace}/serviceaccounts/{name} |             |
| [**replaceNamespacedServiceStatus**](CoreV1Api.md#replaceNamespacedServiceStatus) | **PUT** /api/v1/namespaces/{namespace}/services/{name}/status |             |
| [**replaceNode**](CoreV1Api.md#replaceNode)                  | **PUT** /api/v1/nodes/{name}                                 |             |
| [**replaceNodeStatus**](CoreV1Api.md#replaceNodeStatus)      | **PUT** /api/v1/nodes/{name}/status                          |             |
| [**replacePersistentVolume**](CoreV1Api.md#replacePersistentVolume) | **PUT** /api/v1/persistentvolumes/{name}                     |             |
| [**replacePersistentVolumeStatus**](CoreV1Api.md#replacePersistentVolumeStatus) | **PUT** /api/v1/persistentvolumes/{name}/status              |             |


<a name="connectDeleteNamespacedPodProxy"></a>
# **connectDeleteNamespacedPodProxy**
> String connectDeleteNamespacedPodProxy(name, namespace, path)



connect DELETE requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectDeleteNamespacedPodProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectDeleteNamespacedPodProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectDeleteNamespacedPodProxyWithPath"></a>
# **connectDeleteNamespacedPodProxyWithPath**
> String connectDeleteNamespacedPodProxyWithPath(name, namespace, path, path2)



connect DELETE requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectDeleteNamespacedPodProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectDeleteNamespacedPodProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectDeleteNamespacedServiceProxy"></a>
# **connectDeleteNamespacedServiceProxy**
> String connectDeleteNamespacedServiceProxy(name, namespace, path)



connect DELETE requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectDeleteNamespacedServiceProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectDeleteNamespacedServiceProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectDeleteNamespacedServiceProxyWithPath"></a>
# **connectDeleteNamespacedServiceProxyWithPath**
> String connectDeleteNamespacedServiceProxyWithPath(name, namespace, path, path2)



connect DELETE requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectDeleteNamespacedServiceProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectDeleteNamespacedServiceProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectDeleteNodeProxy"></a>
# **connectDeleteNodeProxy**
> String connectDeleteNodeProxy(name, path)



connect DELETE requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectDeleteNodeProxy(name, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectDeleteNodeProxy");
    e.printStackTrace();
}
```

### Parameters

| Name     | Type       | Description                                                  | Notes      |
| -------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name** | **String** | name of the NodeProxyOptions                                 |            |
| **path** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectDeleteNodeProxyWithPath"></a>
# **connectDeleteNodeProxyWithPath**
> String connectDeleteNodeProxyWithPath(name, path, path2)



connect DELETE requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectDeleteNodeProxyWithPath(name, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectDeleteNodeProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name      | Type       | Description                                                  | Notes      |
| --------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**  | **String** | name of the NodeProxyOptions                                 |            |
| **path**  | **String** | path to the resource                                         |            |
| **path2** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNamespacedPodAttach"></a>
# **connectGetNamespacedPodAttach**
> String connectGetNamespacedPodAttach(name, namespace, container, stderr, stdin, stdout, tty)



connect GET requests to attach of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodAttachOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String container = "container_example"; // String | The container in which to execute the command. Defaults to only container if there is only one container in the pod.
Boolean stderr = true; // Boolean | Stderr if true indicates that stderr is to be redirected for the attach call. Defaults to true.
Boolean stdin = true; // Boolean | Stdin if true, redirects the standard input stream of the pod for this call. Defaults to false.
Boolean stdout = true; // Boolean | Stdout if true indicates that stdout is to be redirected for the attach call. Defaults to true.
Boolean tty = true; // Boolean | TTY if true indicates that a tty will be allocated for the attach call. This is passed through the container runtime so the tty is allocated on the worker node by the container runtime. Defaults to false.
try {
    String result = apiInstance.connectGetNamespacedPodAttach(name, namespace, container, stderr, stdin, stdout, tty);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNamespacedPodAttach");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type        | Description                                                  | Notes      |
| ------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String**  | name of the PodAttachOptions                                 |            |
| **namespace** | **String**  | object name and auth scope, such as for teams and projects   |            |
| **container** | **String**  | The container in which to execute the command. Defaults to only container if there is only one container in the pod. | [optional] |
| **stderr**    | **Boolean** | Stderr if true indicates that stderr is to be redirected for the attach call. Defaults to true. | [optional] |
| **stdin**     | **Boolean** | Stdin if true, redirects the standard input stream of the pod for this call. Defaults to false. | [optional] |
| **stdout**    | **Boolean** | Stdout if true indicates that stdout is to be redirected for the attach call. Defaults to true. | [optional] |
| **tty**       | **Boolean** | TTY if true indicates that a tty will be allocated for the attach call. This is passed through the container runtime so the tty is allocated on the worker node by the container runtime. Defaults to false. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNamespacedPodExec"></a>
# **connectGetNamespacedPodExec**
> String connectGetNamespacedPodExec(name, namespace, command, container, stderr, stdin, stdout, tty)



connect GET requests to exec of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodExecOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String command = "command_example"; // String | Command is the remote command to execute. argv array. Not executed within a shell.
String container = "container_example"; // String | Container in which to execute the command. Defaults to only container if there is only one container in the pod.
Boolean stderr = true; // Boolean | Redirect the standard error stream of the pod for this call. Defaults to true.
Boolean stdin = true; // Boolean | Redirect the standard input stream of the pod for this call. Defaults to false.
Boolean stdout = true; // Boolean | Redirect the standard output stream of the pod for this call. Defaults to true.
Boolean tty = true; // Boolean | TTY if true indicates that a tty will be allocated for the exec call. Defaults to false.
try {
    String result = apiInstance.connectGetNamespacedPodExec(name, namespace, command, container, stderr, stdin, stdout, tty);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNamespacedPodExec");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type        | Description                                                  | Notes      |
| ------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String**  | name of the PodExecOptions                                   |            |
| **namespace** | **String**  | object name and auth scope, such as for teams and projects   |            |
| **command**   | **String**  | Command is the remote command to execute. argv array. Not executed within a shell. | [optional] |
| **container** | **String**  | Container in which to execute the command. Defaults to only container if there is only one container in the pod. | [optional] |
| **stderr**    | **Boolean** | Redirect the standard error stream of the pod for this call. Defaults to true. | [optional] |
| **stdin**     | **Boolean** | Redirect the standard input stream of the pod for this call. Defaults to false. | [optional] |
| **stdout**    | **Boolean** | Redirect the standard output stream of the pod for this call. Defaults to true. | [optional] |
| **tty**       | **Boolean** | TTY if true indicates that a tty will be allocated for the exec call. Defaults to false. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNamespacedPodPortforward"></a>
# **connectGetNamespacedPodPortforward**
> String connectGetNamespacedPodPortforward(name, namespace, ports)



connect GET requests to portforward of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodPortForwardOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
Integer ports = 56; // Integer | List of ports to forward Required when using WebSockets
try {
    String result = apiInstance.connectGetNamespacedPodPortforward(name, namespace, ports);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNamespacedPodPortforward");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type        | Description                                                | Notes      |
| ------------- | ----------- | ---------------------------------------------------------- | ---------- |
| **name**      | **String**  | name of the PodPortForwardOptions                          |            |
| **namespace** | **String**  | object name and auth scope, such as for teams and projects |            |
| **ports**     | **Integer** | List of ports to forward Required when using WebSockets    | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNamespacedPodProxy"></a>
# **connectGetNamespacedPodProxy**
> String connectGetNamespacedPodProxy(name, namespace, path)



connect GET requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectGetNamespacedPodProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNamespacedPodProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNamespacedPodProxyWithPath"></a>
# **connectGetNamespacedPodProxyWithPath**
> String connectGetNamespacedPodProxyWithPath(name, namespace, path, path2)



connect GET requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectGetNamespacedPodProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNamespacedPodProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNamespacedServiceProxy"></a>
# **connectGetNamespacedServiceProxy**
> String connectGetNamespacedServiceProxy(name, namespace, path)



connect GET requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectGetNamespacedServiceProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNamespacedServiceProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNamespacedServiceProxyWithPath"></a>
# **connectGetNamespacedServiceProxyWithPath**
> String connectGetNamespacedServiceProxyWithPath(name, namespace, path, path2)



connect GET requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectGetNamespacedServiceProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNamespacedServiceProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNodeProxy"></a>
# **connectGetNodeProxy**
> String connectGetNodeProxy(name, path)



connect GET requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectGetNodeProxy(name, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNodeProxy");
    e.printStackTrace();
}
```

### Parameters

| Name     | Type       | Description                                                  | Notes      |
| -------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name** | **String** | name of the NodeProxyOptions                                 |            |
| **path** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectGetNodeProxyWithPath"></a>
# **connectGetNodeProxyWithPath**
> String connectGetNodeProxyWithPath(name, path, path2)



connect GET requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectGetNodeProxyWithPath(name, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectGetNodeProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name      | Type       | Description                                                  | Notes      |
| --------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**  | **String** | name of the NodeProxyOptions                                 |            |
| **path**  | **String** | path to the resource                                         |            |
| **path2** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectHeadNamespacedPodProxy"></a>
# **connectHeadNamespacedPodProxy**
> String connectHeadNamespacedPodProxy(name, namespace, path)



connect HEAD requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectHeadNamespacedPodProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectHeadNamespacedPodProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectHeadNamespacedPodProxyWithPath"></a>
# **connectHeadNamespacedPodProxyWithPath**
> String connectHeadNamespacedPodProxyWithPath(name, namespace, path, path2)



connect HEAD requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectHeadNamespacedPodProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectHeadNamespacedPodProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectHeadNamespacedServiceProxy"></a>
# **connectHeadNamespacedServiceProxy**
> String connectHeadNamespacedServiceProxy(name, namespace, path)



connect HEAD requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectHeadNamespacedServiceProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectHeadNamespacedServiceProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectHeadNamespacedServiceProxyWithPath"></a>
# **connectHeadNamespacedServiceProxyWithPath**
> String connectHeadNamespacedServiceProxyWithPath(name, namespace, path, path2)



connect HEAD requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectHeadNamespacedServiceProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectHeadNamespacedServiceProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectHeadNodeProxy"></a>
# **connectHeadNodeProxy**
> String connectHeadNodeProxy(name, path)



connect HEAD requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectHeadNodeProxy(name, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectHeadNodeProxy");
    e.printStackTrace();
}
```

### Parameters

| Name     | Type       | Description                                                  | Notes      |
| -------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name** | **String** | name of the NodeProxyOptions                                 |            |
| **path** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectHeadNodeProxyWithPath"></a>
# **connectHeadNodeProxyWithPath**
> String connectHeadNodeProxyWithPath(name, path, path2)



connect HEAD requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectHeadNodeProxyWithPath(name, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectHeadNodeProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name      | Type       | Description                                                  | Notes      |
| --------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**  | **String** | name of the NodeProxyOptions                                 |            |
| **path**  | **String** | path to the resource                                         |            |
| **path2** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectOptionsNamespacedPodProxy"></a>
# **connectOptionsNamespacedPodProxy**
> String connectOptionsNamespacedPodProxy(name, namespace, path)



connect OPTIONS requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectOptionsNamespacedPodProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectOptionsNamespacedPodProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectOptionsNamespacedPodProxyWithPath"></a>
# **connectOptionsNamespacedPodProxyWithPath**
> String connectOptionsNamespacedPodProxyWithPath(name, namespace, path, path2)



connect OPTIONS requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectOptionsNamespacedPodProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectOptionsNamespacedPodProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectOptionsNamespacedServiceProxy"></a>
# **connectOptionsNamespacedServiceProxy**
> String connectOptionsNamespacedServiceProxy(name, namespace, path)



connect OPTIONS requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectOptionsNamespacedServiceProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectOptionsNamespacedServiceProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectOptionsNamespacedServiceProxyWithPath"></a>
# **connectOptionsNamespacedServiceProxyWithPath**
> String connectOptionsNamespacedServiceProxyWithPath(name, namespace, path, path2)



connect OPTIONS requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectOptionsNamespacedServiceProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectOptionsNamespacedServiceProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectOptionsNodeProxy"></a>
# **connectOptionsNodeProxy**
> String connectOptionsNodeProxy(name, path)



connect OPTIONS requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectOptionsNodeProxy(name, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectOptionsNodeProxy");
    e.printStackTrace();
}
```

### Parameters

| Name     | Type       | Description                                                  | Notes      |
| -------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name** | **String** | name of the NodeProxyOptions                                 |            |
| **path** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectOptionsNodeProxyWithPath"></a>
# **connectOptionsNodeProxyWithPath**
> String connectOptionsNodeProxyWithPath(name, path, path2)



connect OPTIONS requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectOptionsNodeProxyWithPath(name, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectOptionsNodeProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name      | Type       | Description                                                  | Notes      |
| --------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**  | **String** | name of the NodeProxyOptions                                 |            |
| **path**  | **String** | path to the resource                                         |            |
| **path2** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPatchNamespacedPodProxy"></a>
# **connectPatchNamespacedPodProxy**
> String connectPatchNamespacedPodProxy(name, namespace, path)



connect PATCH requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectPatchNamespacedPodProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPatchNamespacedPodProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPatchNamespacedPodProxyWithPath"></a>
# **connectPatchNamespacedPodProxyWithPath**
> String connectPatchNamespacedPodProxyWithPath(name, namespace, path, path2)



connect PATCH requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectPatchNamespacedPodProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPatchNamespacedPodProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPatchNamespacedServiceProxy"></a>
# **connectPatchNamespacedServiceProxy**
> String connectPatchNamespacedServiceProxy(name, namespace, path)



connect PATCH requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectPatchNamespacedServiceProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPatchNamespacedServiceProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPatchNamespacedServiceProxyWithPath"></a>
# **connectPatchNamespacedServiceProxyWithPath**
> String connectPatchNamespacedServiceProxyWithPath(name, namespace, path, path2)



connect PATCH requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectPatchNamespacedServiceProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPatchNamespacedServiceProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPatchNodeProxy"></a>
# **connectPatchNodeProxy**
> String connectPatchNodeProxy(name, path)



connect PATCH requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectPatchNodeProxy(name, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPatchNodeProxy");
    e.printStackTrace();
}
```

### Parameters

| Name     | Type       | Description                                                  | Notes      |
| -------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name** | **String** | name of the NodeProxyOptions                                 |            |
| **path** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPatchNodeProxyWithPath"></a>
# **connectPatchNodeProxyWithPath**
> String connectPatchNodeProxyWithPath(name, path, path2)



connect PATCH requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectPatchNodeProxyWithPath(name, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPatchNodeProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name      | Type       | Description                                                  | Notes      |
| --------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**  | **String** | name of the NodeProxyOptions                                 |            |
| **path**  | **String** | path to the resource                                         |            |
| **path2** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNamespacedPodAttach"></a>
# **connectPostNamespacedPodAttach**
> String connectPostNamespacedPodAttach(name, namespace, container, stderr, stdin, stdout, tty)



connect POST requests to attach of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodAttachOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String container = "container_example"; // String | The container in which to execute the command. Defaults to only container if there is only one container in the pod.
Boolean stderr = true; // Boolean | Stderr if true indicates that stderr is to be redirected for the attach call. Defaults to true.
Boolean stdin = true; // Boolean | Stdin if true, redirects the standard input stream of the pod for this call. Defaults to false.
Boolean stdout = true; // Boolean | Stdout if true indicates that stdout is to be redirected for the attach call. Defaults to true.
Boolean tty = true; // Boolean | TTY if true indicates that a tty will be allocated for the attach call. This is passed through the container runtime so the tty is allocated on the worker node by the container runtime. Defaults to false.
try {
    String result = apiInstance.connectPostNamespacedPodAttach(name, namespace, container, stderr, stdin, stdout, tty);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNamespacedPodAttach");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type        | Description                                                  | Notes      |
| ------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String**  | name of the PodAttachOptions                                 |            |
| **namespace** | **String**  | object name and auth scope, such as for teams and projects   |            |
| **container** | **String**  | The container in which to execute the command. Defaults to only container if there is only one container in the pod. | [optional] |
| **stderr**    | **Boolean** | Stderr if true indicates that stderr is to be redirected for the attach call. Defaults to true. | [optional] |
| **stdin**     | **Boolean** | Stdin if true, redirects the standard input stream of the pod for this call. Defaults to false. | [optional] |
| **stdout**    | **Boolean** | Stdout if true indicates that stdout is to be redirected for the attach call. Defaults to true. | [optional] |
| **tty**       | **Boolean** | TTY if true indicates that a tty will be allocated for the attach call. This is passed through the container runtime so the tty is allocated on the worker node by the container runtime. Defaults to false. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNamespacedPodExec"></a>
# **connectPostNamespacedPodExec**
> String connectPostNamespacedPodExec(name, namespace, command, container, stderr, stdin, stdout, tty)



connect POST requests to exec of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodExecOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String command = "command_example"; // String | Command is the remote command to execute. argv array. Not executed within a shell.
String container = "container_example"; // String | Container in which to execute the command. Defaults to only container if there is only one container in the pod.
Boolean stderr = true; // Boolean | Redirect the standard error stream of the pod for this call. Defaults to true.
Boolean stdin = true; // Boolean | Redirect the standard input stream of the pod for this call. Defaults to false.
Boolean stdout = true; // Boolean | Redirect the standard output stream of the pod for this call. Defaults to true.
Boolean tty = true; // Boolean | TTY if true indicates that a tty will be allocated for the exec call. Defaults to false.
try {
    String result = apiInstance.connectPostNamespacedPodExec(name, namespace, command, container, stderr, stdin, stdout, tty);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNamespacedPodExec");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type        | Description                                                  | Notes      |
| ------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String**  | name of the PodExecOptions                                   |            |
| **namespace** | **String**  | object name and auth scope, such as for teams and projects   |            |
| **command**   | **String**  | Command is the remote command to execute. argv array. Not executed within a shell. | [optional] |
| **container** | **String**  | Container in which to execute the command. Defaults to only container if there is only one container in the pod. | [optional] |
| **stderr**    | **Boolean** | Redirect the standard error stream of the pod for this call. Defaults to true. | [optional] |
| **stdin**     | **Boolean** | Redirect the standard input stream of the pod for this call. Defaults to false. | [optional] |
| **stdout**    | **Boolean** | Redirect the standard output stream of the pod for this call. Defaults to true. | [optional] |
| **tty**       | **Boolean** | TTY if true indicates that a tty will be allocated for the exec call. Defaults to false. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNamespacedPodPortforward"></a>
# **connectPostNamespacedPodPortforward**
> String connectPostNamespacedPodPortforward(name, namespace, ports)



connect POST requests to portforward of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodPortForwardOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
Integer ports = 56; // Integer | List of ports to forward Required when using WebSockets
try {
    String result = apiInstance.connectPostNamespacedPodPortforward(name, namespace, ports);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNamespacedPodPortforward");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type        | Description                                                | Notes      |
| ------------- | ----------- | ---------------------------------------------------------- | ---------- |
| **name**      | **String**  | name of the PodPortForwardOptions                          |            |
| **namespace** | **String**  | object name and auth scope, such as for teams and projects |            |
| **ports**     | **Integer** | List of ports to forward Required when using WebSockets    | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNamespacedPodProxy"></a>
# **connectPostNamespacedPodProxy**
> String connectPostNamespacedPodProxy(name, namespace, path)



connect POST requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectPostNamespacedPodProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNamespacedPodProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNamespacedPodProxyWithPath"></a>
# **connectPostNamespacedPodProxyWithPath**
> String connectPostNamespacedPodProxyWithPath(name, namespace, path, path2)



connect POST requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectPostNamespacedPodProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNamespacedPodProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNamespacedServiceProxy"></a>
# **connectPostNamespacedServiceProxy**
> String connectPostNamespacedServiceProxy(name, namespace, path)



connect POST requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectPostNamespacedServiceProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNamespacedServiceProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNamespacedServiceProxyWithPath"></a>
# **connectPostNamespacedServiceProxyWithPath**
> String connectPostNamespacedServiceProxyWithPath(name, namespace, path, path2)



connect POST requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectPostNamespacedServiceProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNamespacedServiceProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNodeProxy"></a>
# **connectPostNodeProxy**
> String connectPostNodeProxy(name, path)



connect POST requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectPostNodeProxy(name, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNodeProxy");
    e.printStackTrace();
}
```

### Parameters

| Name     | Type       | Description                                                  | Notes      |
| -------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name** | **String** | name of the NodeProxyOptions                                 |            |
| **path** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPostNodeProxyWithPath"></a>
# **connectPostNodeProxyWithPath**
> String connectPostNodeProxyWithPath(name, path, path2)



connect POST requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectPostNodeProxyWithPath(name, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPostNodeProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name      | Type       | Description                                                  | Notes      |
| --------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**  | **String** | name of the NodeProxyOptions                                 |            |
| **path**  | **String** | path to the resource                                         |            |
| **path2** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPutNamespacedPodProxy"></a>
# **connectPutNamespacedPodProxy**
> String connectPutNamespacedPodProxy(name, namespace, path)



connect PUT requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectPutNamespacedPodProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPutNamespacedPodProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPutNamespacedPodProxyWithPath"></a>
# **connectPutNamespacedPodProxyWithPath**
> String connectPutNamespacedPodProxyWithPath(name, namespace, path, path2)



connect PUT requests to proxy of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to pod.
try {
    String result = apiInstance.connectPutNamespacedPodProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPutNamespacedPodProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the PodProxyOptions                                  |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the URL path to use for the current proxy request to pod. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPutNamespacedServiceProxy"></a>
# **connectPutNamespacedServiceProxy**
> String connectPutNamespacedServiceProxy(name, namespace, path)



connect PUT requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectPutNamespacedServiceProxy(name, namespace, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPutNamespacedServiceProxy");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPutNamespacedServiceProxyWithPath"></a>
# **connectPutNamespacedServiceProxyWithPath**
> String connectPutNamespacedServiceProxyWithPath(name, namespace, path, path2)



connect PUT requests to proxy of Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceProxyOptions
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q=user:kimchy. Path is _search?q=user:kimchy.
try {
    String result = apiInstance.connectPutNamespacedServiceProxyWithPath(name, namespace, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPutNamespacedServiceProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name          | Type       | Description                                                  | Notes      |
| ------------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**      | **String** | name of the ServiceProxyOptions                              |            |
| **namespace** | **String** | object name and auth scope, such as for teams and projects   |            |
| **path**      | **String** | path to the resource                                         |            |
| **path2**     | **String** | Path is the part of URLs that include service endpoints, suffixes, and parameters to use for the current proxy request to service. For example, the whole request URL is http://localhost/api/v1/namespaces/kube-system/services/elasticsearch-logging/_search?q&#x3D;user:kimchy. Path is _search?q&#x3D;user:kimchy. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPutNodeProxy"></a>
# **connectPutNodeProxy**
> String connectPutNodeProxy(name, path)



connect PUT requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectPutNodeProxy(name, path);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPutNodeProxy");
    e.printStackTrace();
}
```

### Parameters

| Name     | Type       | Description                                                  | Notes      |
| -------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name** | **String** | name of the NodeProxyOptions                                 |            |
| **path** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="connectPutNodeProxyWithPath"></a>
# **connectPutNodeProxyWithPath**
> String connectPutNodeProxyWithPath(name, path, path2)



connect PUT requests to proxy of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the NodeProxyOptions
String path = "path_example"; // String | path to the resource
String path2 = "path_example"; // String | Path is the URL path to use for the current proxy request to node.
try {
    String result = apiInstance.connectPutNodeProxyWithPath(name, path, path2);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#connectPutNodeProxyWithPath");
    e.printStackTrace();
}
```

### Parameters

| Name      | Type       | Description                                                  | Notes      |
| --------- | ---------- | ------------------------------------------------------------ | ---------- |
| **name**  | **String** | name of the NodeProxyOptions                                 |            |
| **path**  | **String** | path to the resource                                         |            |
| **path2** | **String** | Path is the URL path to use for the current proxy request to node. | [optional] |

### Return type

**String**

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

<a name="createNamespace"></a>
# **createNamespace**
> V1Namespace createNamespace(body, pretty, dryRun, fieldManager)



create a Namespace

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
V1Namespace body = new V1Namespace(); // V1Namespace | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1Namespace result = apiInstance.createNamespace(body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespace");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                              | Description                                                  | Notes      |
| ---------------- | --------------------------------- | ------------------------------------------------------------ | ---------- |
| **body**         | [**V1Namespace**](V1Namespace.md) |                                                              |            |
| **pretty**       | **String**                        | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                        | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                        | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1Namespace**](V1Namespace.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedBinding"></a>
# **createNamespacedBinding**
> V1Binding createNamespacedBinding(namespace, body, dryRun, fieldManager, pretty)



create a Binding

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1Binding body = new V1Binding(); // V1Binding | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
try {
    V1Binding result = apiInstance.createNamespacedBinding(namespace, body, dryRun, fieldManager, pretty);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedBinding");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                          | Description                                                  | Notes      |
| ---------------- | ----------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                    | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1Binding**](V1Binding.md) |                                                              |            |
| **dryRun**       | **String**                    | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                    | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |
| **pretty**       | **String**                    | If &#39;true&#39;, then the output is pretty printed.        | [optional] |

### Return type

[**V1Binding**](V1Binding.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedConfigMap"></a>
# **createNamespacedConfigMap**
> V1ConfigMap createNamespacedConfigMap(namespace, body, pretty, dryRun, fieldManager)



create a ConfigMap

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1ConfigMap body = new V1ConfigMap(); // V1ConfigMap | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1ConfigMap result = apiInstance.createNamespacedConfigMap(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedConfigMap");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                              | Description                                                  | Notes      |
| ---------------- | --------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                        | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1ConfigMap**](V1ConfigMap.md) |                                                              |            |
| **pretty**       | **String**                        | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                        | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                        | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1ConfigMap**](V1ConfigMap.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedEndpoints"></a>
# **createNamespacedEndpoints**
> V1Endpoints createNamespacedEndpoints(namespace, body, pretty, dryRun, fieldManager)



create Endpoints

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1Endpoints body = new V1Endpoints(); // V1Endpoints | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1Endpoints result = apiInstance.createNamespacedEndpoints(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedEndpoints");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                              | Description                                                  | Notes      |
| ---------------- | --------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                        | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1Endpoints**](V1Endpoints.md) |                                                              |            |
| **pretty**       | **String**                        | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                        | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                        | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1Endpoints**](V1Endpoints.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedEvent"></a>
# **createNamespacedEvent**
> V1Event createNamespacedEvent(namespace, body, pretty, dryRun, fieldManager)



create an Event

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1Event body = new V1Event(); // V1Event | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1Event result = apiInstance.createNamespacedEvent(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedEvent");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                      | Description                                                  | Notes      |
| ---------------- | ------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1Event**](V1Event.md) |                                                              |            |
| **pretty**       | **String**                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1Event**](V1Event.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedLimitRange"></a>
# **createNamespacedLimitRange**
> V1LimitRange createNamespacedLimitRange(namespace, body, pretty, dryRun, fieldManager)



create a LimitRange

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1LimitRange body = new V1LimitRange(); // V1LimitRange | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1LimitRange result = apiInstance.createNamespacedLimitRange(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedLimitRange");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                | Description                                                  | Notes      |
| ---------------- | ----------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                          | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1LimitRange**](V1LimitRange.md) |                                                              |            |
| **pretty**       | **String**                          | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                          | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                          | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1LimitRange**](V1LimitRange.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedPersistentVolumeClaim"></a>
# **createNamespacedPersistentVolumeClaim**
> V1PersistentVolumeClaim createNamespacedPersistentVolumeClaim(namespace, body, pretty, dryRun, fieldManager)



create a PersistentVolumeClaim

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1PersistentVolumeClaim body = new V1PersistentVolumeClaim(); // V1PersistentVolumeClaim | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1PersistentVolumeClaim result = apiInstance.createNamespacedPersistentVolumeClaim(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedPersistentVolumeClaim");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                                      | Description                                                  | Notes      |
| ---------------- | --------------------------------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                                                | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1PersistentVolumeClaim**](V1PersistentVolumeClaim.md) |                                                              |            |
| **pretty**       | **String**                                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                                                | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1PersistentVolumeClaim**](V1PersistentVolumeClaim.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedPod"></a>
# **createNamespacedPod**
> V1Pod createNamespacedPod(namespace, body, pretty, dryRun, fieldManager)



create a Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1Pod body = new V1Pod(); // V1Pod | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1Pod result = apiInstance.createNamespacedPod(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedPod");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                  | Description                                                  | Notes      |
| ---------------- | --------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**            | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1Pod**](V1Pod.md) |                                                              |            |
| **pretty**       | **String**            | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**            | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**            | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1Pod**](V1Pod.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedPodBinding"></a>
# **createNamespacedPodBinding**
> V1Binding createNamespacedPodBinding(name, namespace, body, dryRun, fieldManager, pretty)



create binding of a Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Binding
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1Binding body = new V1Binding(); // V1Binding | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
try {
    V1Binding result = apiInstance.createNamespacedPodBinding(name, namespace, body, dryRun, fieldManager, pretty);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedPodBinding");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                          | Description                                                  | Notes      |
| ---------------- | ----------------------------- | ------------------------------------------------------------ | ---------- |
| **name**         | **String**                    | name of the Binding                                          |            |
| **namespace**    | **String**                    | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1Binding**](V1Binding.md) |                                                              |            |
| **dryRun**       | **String**                    | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                    | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |
| **pretty**       | **String**                    | If &#39;true&#39;, then the output is pretty printed.        | [optional] |

### Return type

[**V1Binding**](V1Binding.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedPodEviction"></a>
# **createNamespacedPodEviction**
> V1beta1Eviction createNamespacedPodEviction(name, namespace, body, dryRun, fieldManager, pretty)



create eviction of a Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Eviction
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1beta1Eviction body = new V1beta1Eviction(); // V1beta1Eviction | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
try {
    V1beta1Eviction result = apiInstance.createNamespacedPodEviction(name, namespace, body, dryRun, fieldManager, pretty);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedPodEviction");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                      | Description                                                  | Notes      |
| ---------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**         | **String**                                | name of the Eviction                                         |            |
| **namespace**    | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1beta1Eviction**](V1beta1Eviction.md) |                                                              |            |
| **dryRun**       | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                                | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |
| **pretty**       | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |

### Return type

[**V1beta1Eviction**](V1beta1Eviction.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedPodTemplate"></a>
# **createNamespacedPodTemplate**
> V1PodTemplate createNamespacedPodTemplate(namespace, body, pretty, dryRun, fieldManager)



create a PodTemplate

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1PodTemplate body = new V1PodTemplate(); // V1PodTemplate | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1PodTemplate result = apiInstance.createNamespacedPodTemplate(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedPodTemplate");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                  | Description                                                  | Notes      |
| ---------------- | ------------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                            | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1PodTemplate**](V1PodTemplate.md) |                                                              |            |
| **pretty**       | **String**                            | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                            | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                            | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1PodTemplate**](V1PodTemplate.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedReplicationController"></a>
# **createNamespacedReplicationController**
> V1ReplicationController createNamespacedReplicationController(namespace, body, pretty, dryRun, fieldManager)



create a ReplicationController

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1ReplicationController body = new V1ReplicationController(); // V1ReplicationController | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1ReplicationController result = apiInstance.createNamespacedReplicationController(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedReplicationController");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                                      | Description                                                  | Notes      |
| ---------------- | --------------------------------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                                                | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1ReplicationController**](V1ReplicationController.md) |                                                              |            |
| **pretty**       | **String**                                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                                                | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1ReplicationController**](V1ReplicationController.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedResourceQuota"></a>
# **createNamespacedResourceQuota**
> V1ResourceQuota createNamespacedResourceQuota(namespace, body, pretty, dryRun, fieldManager)



create a ResourceQuota

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1ResourceQuota body = new V1ResourceQuota(); // V1ResourceQuota | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1ResourceQuota result = apiInstance.createNamespacedResourceQuota(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedResourceQuota");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                      | Description                                                  | Notes      |
| ---------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1ResourceQuota**](V1ResourceQuota.md) |                                                              |            |
| **pretty**       | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                                | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1ResourceQuota**](V1ResourceQuota.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedSecret"></a>
# **createNamespacedSecret**
> V1Secret createNamespacedSecret(namespace, body, pretty, dryRun, fieldManager)



create a Secret

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1Secret body = new V1Secret(); // V1Secret | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1Secret result = apiInstance.createNamespacedSecret(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedSecret");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                        | Description                                                  | Notes      |
| ---------------- | --------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                  | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1Secret**](V1Secret.md) |                                                              |            |
| **pretty**       | **String**                  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                  | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                  | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1Secret**](V1Secret.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedService"></a>
# **createNamespacedService**
> V1Service createNamespacedService(namespace, body, pretty, dryRun, fieldManager)



create a Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1Service body = new V1Service(); // V1Service | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1Service result = apiInstance.createNamespacedService(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedService");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                          | Description                                                  | Notes      |
| ---------------- | ----------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                    | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1Service**](V1Service.md) |                                                              |            |
| **pretty**       | **String**                    | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                    | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                    | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1Service**](V1Service.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNamespacedServiceAccount"></a>
# **createNamespacedServiceAccount**
> V1ServiceAccount createNamespacedServiceAccount(namespace, body, pretty, dryRun, fieldManager)



create a ServiceAccount

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
V1ServiceAccount body = new V1ServiceAccount(); // V1ServiceAccount | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1ServiceAccount result = apiInstance.createNamespacedServiceAccount(namespace, body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNamespacedServiceAccount");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                        | Description                                                  | Notes      |
| ---------------- | ------------------------------------------- | ------------------------------------------------------------ | ---------- |
| **namespace**    | **String**                                  | object name and auth scope, such as for teams and projects   |            |
| **body**         | [**V1ServiceAccount**](V1ServiceAccount.md) |                                                              |            |
| **pretty**       | **String**                                  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                                  | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                                  | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1ServiceAccount**](V1ServiceAccount.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createNode"></a>
# **createNode**
> V1Node createNode(body, pretty, dryRun, fieldManager)



create a Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
V1Node body = new V1Node(); // V1Node | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1Node result = apiInstance.createNode(body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createNode");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                    | Description                                                  | Notes      |
| ---------------- | ----------------------- | ------------------------------------------------------------ | ---------- |
| **body**         | [**V1Node**](V1Node.md) |                                                              |            |
| **pretty**       | **String**              | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**              | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**              | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1Node**](V1Node.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="createPersistentVolume"></a>
# **createPersistentVolume**
> V1PersistentVolume createPersistentVolume(body, pretty, dryRun, fieldManager)



create a PersistentVolume

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
V1PersistentVolume body = new V1PersistentVolume(); // V1PersistentVolume | 
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
String fieldManager = "fieldManager_example"; // String | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint.
try {
    V1PersistentVolume result = apiInstance.createPersistentVolume(body, pretty, dryRun, fieldManager);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#createPersistentVolume");
    e.printStackTrace();
}
```

### Parameters

| Name             | Type                                            | Description                                                  | Notes      |
| ---------------- | ----------------------------------------------- | ------------------------------------------------------------ | ---------- |
| **body**         | [**V1PersistentVolume**](V1PersistentVolume.md) |                                                              |            |
| **pretty**       | **String**                                      | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **dryRun**       | **String**                                      | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **fieldManager** | **String**                                      | fieldManager is a name associated with the actor or entity that is making these changes. The value must be less than or 128 characters long, and only contain printable characters, as defined by https://golang.org/pkg/unicode/#IsPrint. | [optional] |

### Return type

[**V1PersistentVolume**](V1PersistentVolume.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedConfigMap"></a>
# **deleteCollectionNamespacedConfigMap**
> V1Status deleteCollectionNamespacedConfigMap(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of ConfigMap

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedConfigMap(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedConfigMap");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedEndpoints"></a>
# **deleteCollectionNamespacedEndpoints**
> V1Status deleteCollectionNamespacedEndpoints(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of Endpoints

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedEndpoints(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedEndpoints");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedEvent"></a>
# **deleteCollectionNamespacedEvent**
> V1Status deleteCollectionNamespacedEvent(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of Event

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedEvent(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedEvent");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedLimitRange"></a>
# **deleteCollectionNamespacedLimitRange**
> V1Status deleteCollectionNamespacedLimitRange(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of LimitRange

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedLimitRange(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedLimitRange");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedPersistentVolumeClaim"></a>
# **deleteCollectionNamespacedPersistentVolumeClaim**
> V1Status deleteCollectionNamespacedPersistentVolumeClaim(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of PersistentVolumeClaim

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedPersistentVolumeClaim(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedPersistentVolumeClaim");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedPod"></a>
# **deleteCollectionNamespacedPod**
> V1Status deleteCollectionNamespacedPod(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedPod(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedPod");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedPodTemplate"></a>
# **deleteCollectionNamespacedPodTemplate**
> V1Status deleteCollectionNamespacedPodTemplate(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of PodTemplate

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedPodTemplate(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedPodTemplate");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedReplicationController"></a>
# **deleteCollectionNamespacedReplicationController**
> V1Status deleteCollectionNamespacedReplicationController(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of ReplicationController

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedReplicationController(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedReplicationController");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedResourceQuota"></a>
# **deleteCollectionNamespacedResourceQuota**
> V1Status deleteCollectionNamespacedResourceQuota(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of ResourceQuota

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedResourceQuota(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedResourceQuota");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedSecret"></a>
# **deleteCollectionNamespacedSecret**
> V1Status deleteCollectionNamespacedSecret(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of Secret

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedSecret(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedSecret");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNamespacedServiceAccount"></a>
# **deleteCollectionNamespacedServiceAccount**
> V1Status deleteCollectionNamespacedServiceAccount(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of ServiceAccount

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNamespacedServiceAccount(namespace, pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNamespacedServiceAccount");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **namespace**       | **String**  | object name and auth scope, such as for teams and projects   |            |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionNode"></a>
# **deleteCollectionNode**
> V1Status deleteCollectionNode(pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionNode(pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionNode");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteCollectionPersistentVolume"></a>
# **deleteCollectionPersistentVolume**
> V1Status deleteCollectionPersistentVolume(pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch)



delete collection of PersistentVolume

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1Status result = apiInstance.deleteCollectionPersistentVolume(pretty, _continue, fieldSelector, labelSelector, limit, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteCollectionPersistentVolume");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespace"></a>
# **deleteNamespace**
> V1Status deleteNamespace(name, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a Namespace

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Namespace
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespace(name, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespace");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the Namespace                                        |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedConfigMap"></a>
# **deleteNamespacedConfigMap**
> V1Status deleteNamespacedConfigMap(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a ConfigMap

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ConfigMap
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedConfigMap(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedConfigMap");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the ConfigMap                                        |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedEndpoints"></a>
# **deleteNamespacedEndpoints**
> V1Status deleteNamespacedEndpoints(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete Endpoints

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Endpoints
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedEndpoints(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedEndpoints");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the Endpoints                                        |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedEvent"></a>
# **deleteNamespacedEvent**
> V1Status deleteNamespacedEvent(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete an Event

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Event
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedEvent(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedEvent");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the Event                                            |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedLimitRange"></a>
# **deleteNamespacedLimitRange**
> V1Status deleteNamespacedLimitRange(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a LimitRange

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the LimitRange
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedLimitRange(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedLimitRange");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the LimitRange                                       |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedPersistentVolumeClaim"></a>
# **deleteNamespacedPersistentVolumeClaim**
> V1Status deleteNamespacedPersistentVolumeClaim(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a PersistentVolumeClaim

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PersistentVolumeClaim
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedPersistentVolumeClaim(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedPersistentVolumeClaim");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the PersistentVolumeClaim                            |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedPod"></a>
# **deleteNamespacedPod**
> V1Status deleteNamespacedPod(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a Pod

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Pod
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedPod(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedPod");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the Pod                                              |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedPodTemplate"></a>
# **deleteNamespacedPodTemplate**
> V1Status deleteNamespacedPodTemplate(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a PodTemplate

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PodTemplate
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedPodTemplate(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedPodTemplate");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the PodTemplate                                      |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedReplicationController"></a>
# **deleteNamespacedReplicationController**
> V1Status deleteNamespacedReplicationController(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a ReplicationController

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ReplicationController
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedReplicationController(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedReplicationController");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the ReplicationController                            |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedResourceQuota"></a>
# **deleteNamespacedResourceQuota**
> V1Status deleteNamespacedResourceQuota(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a ResourceQuota

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ResourceQuota
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedResourceQuota(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedResourceQuota");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the ResourceQuota                                    |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedSecret"></a>
# **deleteNamespacedSecret**
> V1Status deleteNamespacedSecret(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a Secret

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Secret
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedSecret(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedSecret");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the Secret                                           |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedService"></a>
# **deleteNamespacedService**
> V1Status deleteNamespacedService(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a Service

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Service
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedService(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedService");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the Service                                          |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNamespacedServiceAccount"></a>
# **deleteNamespacedServiceAccount**
> V1Status deleteNamespacedServiceAccount(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a ServiceAccount

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the ServiceAccount
String namespace = "namespace_example"; // String | object name and auth scope, such as for teams and projects
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNamespacedServiceAccount(name, namespace, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNamespacedServiceAccount");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the ServiceAccount                                   |            |
| **namespace**          | **String**                                | object name and auth scope, such as for teams and projects   |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deleteNode"></a>
# **deleteNode**
> V1Status deleteNode(name, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a Node

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the Node
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deleteNode(name, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deleteNode");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the Node                                             |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="deletePersistentVolume"></a>
# **deletePersistentVolume**
> V1Status deletePersistentVolume(name, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy)



delete a PersistentVolume

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String name = "name_example"; // String | name of the PersistentVolume
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
V1DeleteOptions body = new V1DeleteOptions(); // V1DeleteOptions | 
String dryRun = "dryRun_example"; // String | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed
Integer gracePeriodSeconds = 56; // Integer | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately.
Boolean orphanDependents = true; // Boolean | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \"orphan\" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.
String propagationPolicy = "propagationPolicy_example"; // String | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: 'Orphan' - orphan the dependents; 'Background' - allow the garbage collector to delete the dependents in the background; 'Foreground' - a cascading policy that deletes all dependents in the foreground.
try {
    V1Status result = apiInstance.deletePersistentVolume(name, pretty, body, dryRun, gracePeriodSeconds, orphanDependents, propagationPolicy);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#deletePersistentVolume");
    e.printStackTrace();
}
```

### Parameters

| Name                   | Type                                      | Description                                                  | Notes      |
| ---------------------- | ----------------------------------------- | ------------------------------------------------------------ | ---------- |
| **name**               | **String**                                | name of the PersistentVolume                                 |            |
| **pretty**             | **String**                                | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **body**               | [**V1DeleteOptions**](V1DeleteOptions.md) |                                                              | [optional] |
| **dryRun**             | **String**                                | When present, indicates that modifications should not be persisted. An invalid or unrecognized dryRun directive will result in an error response and no further processing of the request. Valid values are: - All: all dry run stages will be processed | [optional] |
| **gracePeriodSeconds** | **Integer**                               | The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified. zero means delete immediately. | [optional] |
| **orphanDependents**   | **Boolean**                               | Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the \&quot;orphan\&quot; finalizer will be added to/removed from the object&#39;s finalizers list. Either this field or PropagationPolicy may be set, but not both. | [optional] |
| **propagationPolicy**  | **String**                                | Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy. Acceptable values are: &#39;Orphan&#39; - orphan the dependents; &#39;Background&#39; - allow the garbage collector to delete the dependents in the background; &#39;Foreground&#39; - a cascading policy that deletes all dependents in the foreground. | [optional] |

### Return type

[**V1Status**](V1Status.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="getAPIResources"></a>
# **getAPIResources**
> V1APIResourceList getAPIResources()



get available resources

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
try {
    V1APIResourceList result = apiInstance.getAPIResources();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#getAPIResources");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**V1APIResourceList**](V1APIResourceList.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: application/json, application/yaml, application/vnd.kubernetes.protobuf
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf

<a name="listComponentStatus"></a>
# **listComponentStatus**
> V1ComponentStatusList listComponentStatus(_continue, fieldSelector, labelSelector, limit, pretty, resourceVersion, timeoutSeconds, watch)



list objects of kind ComponentStatus

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1ComponentStatusList result = apiInstance.listComponentStatus(_continue, fieldSelector, labelSelector, limit, pretty, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#listComponentStatus");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1ComponentStatusList**](V1ComponentStatusList.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf, application/json;stream=watch, application/vnd.kubernetes.protobuf;stream=watch

<a name="listConfigMapForAllNamespaces"></a>
# **listConfigMapForAllNamespaces**
> V1ConfigMapList listConfigMapForAllNamespaces(_continue, fieldSelector, labelSelector, limit, pretty, resourceVersion, timeoutSeconds, watch)



list or watch objects of kind ConfigMap

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1ConfigMapList result = apiInstance.listConfigMapForAllNamespaces(_continue, fieldSelector, labelSelector, limit, pretty, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#listConfigMapForAllNamespaces");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1ConfigMapList**](V1ConfigMapList.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf, application/json;stream=watch, application/vnd.kubernetes.protobuf;stream=watch

<a name="listEndpointsForAllNamespaces"></a>
# **listEndpointsForAllNamespaces**
> V1EndpointsList listEndpointsForAllNamespaces(_continue, fieldSelector, labelSelector, limit, pretty, resourceVersion, timeoutSeconds, watch)



list or watch objects of kind Endpoints

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String _continue = "_continue_example"; // String | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \"next key\".  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.
String fieldSelector = "fieldSelector_example"; // String | A selector to restrict the list of returned objects by their fields. Defaults to everything.
String labelSelector = "labelSelector_example"; // String | A selector to restrict the list of returned objects by their labels. Defaults to everything.
Integer limit = 56; // Integer | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the `continue` field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.
String pretty = "pretty_example"; // String | If 'true', then the output is pretty printed.
String resourceVersion = "resourceVersion_example"; // String | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.
Integer timeoutSeconds = 56; // Integer | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity.
Boolean watch = true; // Boolean | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.
try {
    V1EndpointsList result = apiInstance.listEndpointsForAllNamespaces(_continue, fieldSelector, labelSelector, limit, pretty, resourceVersion, timeoutSeconds, watch);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling CoreV1Api#listEndpointsForAllNamespaces");
    e.printStackTrace();
}
```

### Parameters

| Name                | Type        | Description                                                  | Notes      |
| ------------------- | ----------- | ------------------------------------------------------------ | ---------- |
| **_continue**       | **String**  | The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error together with a continue token. If the client needs a consistent list, it must restart their list without the continue field. Otherwise, the client may send another list request with the token received with the 410 error, the server will respond with a list starting from the next key, but from the latest snapshot, which is inconsistent from the previous list results - objects that are created, modified, or deleted after the first list request will be included in the response, as long as their keys are after the \&quot;next key\&quot;.  This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications. | [optional] |
| **fieldSelector**   | **String**  | A selector to restrict the list of returned objects by their fields. Defaults to everything. | [optional] |
| **labelSelector**   | **String**  | A selector to restrict the list of returned objects by their labels. Defaults to everything. | [optional] |
| **limit**           | **Integer** | limit is a maximum number of responses to return for a list call. If more items exist, the server will set the &#x60;continue&#x60; field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.  The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned. | [optional] |
| **pretty**          | **String**  | If &#39;true&#39;, then the output is pretty printed.        | [optional] |
| **resourceVersion** | **String**  | When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it&#39;s 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv. | [optional] |
| **timeoutSeconds**  | **Integer** | Timeout for the list/watch call. This limits the duration of the call, regardless of any activity or inactivity. | [optional] |
| **watch**           | **Boolean** | Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion. | [optional] |

### Return type

[**V1EndpointsList**](V1EndpointsList.md)

### Authorization

[BearerToken](../README.md#BearerToken)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: application/json, application/yaml, application/vnd.kubernetes.protobuf, application/json;stream=watch, application/vnd.kubernetes.protobuf;stream=watch

<a name="listEventForAllNamespaces"></a>
# **listEventForAllNamespaces**
> V1EventList listEventForAllNamespaces(_continue, fieldSelector, labelSelector, limit, pretty, resourceVersion, timeoutSeconds, watch)



list or watch objects of kind Event

### Example
```java
// Import classes:
//import io.kubernetes.client.ApiClient;
//import io.kubernetes.client.ApiException;
//import io.kubernetes.client.Configuration;
//import io.kubernetes.client.auth.*;
//import io.kubernetes.client.apis.CoreV1Api;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure API key authorization: BearerToken
ApiKeyAuth BearerToken = (ApiKeyAuth) defaultClient.getAuthentication("BearerToken");
BearerToken.setApiKey("YOUR API KEY");
// Uncomment the following line to set a prefix for the API key, e.g. "Token" (defaults to null)
//BearerToken.setApiKeyPrefix("Token");

CoreV1Api apiInstance = new CoreV1Api();
String _continue = "_continue_example"; // String | The continue option should be set when 
```