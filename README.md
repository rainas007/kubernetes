# kubernetes
This is for kubernetes tech learning
1 - namespace introducing
Namespace is used for isolate the all kinds of resources in k8s , like object of resource(pod, service, deploymen and so forth) and quota of resource(cpu, memory)

you can use the following command to check all the resources in k8s
# -> kubectl get namespace  (when you create the resources, if you don't assign the namespace, it will use the "default" namespace defaultly)

# -> we will use the yaml file to create the new namespace, please refer to the 1-namespace.yaml

     
