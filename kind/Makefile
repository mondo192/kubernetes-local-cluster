cluster:
	KIND_EXPERIMENTAL_PROVIDER=podman kind create cluster --config multi-node-cluster.yaml

registry: 
	podman run -d -p 5000:5000 --restart always --name registry --net kind registry:2