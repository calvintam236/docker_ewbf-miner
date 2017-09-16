# What is EWBF-Miner?

EWBF-Miner is the console miner provided by [EWBF](https://bitcointalk.org/index.php?topic=1707546.0).

EWBF-Miner supports Zcash (ZEC).

# How to use this image [NVIDIA version]

Run in background:

```console
$ docker run -d --device /dev/nvidia0:/dev/nvidia0 --device /dev/nvidiactl:/dev/nvidiactl --device /dev/nvidia-uvm:/dev/nvidia-uvm --device /dev/nvidia-modeset:/dev/nvidia-modeset --name YOUR_CONTAINER_NAME calvintam236/ewbf-miner:nvidia --server YOUR_POOL_ADDRESS --user YOUR_USERNAME.YOUR_WORKER_NAME --pass YOUR_WORKER_PASSWORD
```

Get `ewbf-miner` options with:

```console
$ docker run --rm calvintam236/ewbf-miner:nvidia
```

Fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```
