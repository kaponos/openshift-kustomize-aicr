Kustomize files that are the basis for openshift deployment of GPU operator.

The namespace creation was not added here on purpose. It is the aicr that creates it.
Note that since aicr is sharing the nfd and GPU operator on the same compoenent (aicr wise) we have to put everything under one namespace.