## EWBF-Miner

### What is it?

EWBF-Miner is the console miner provided by [EWBF](https://bitcointalk.org/index.php?topic=4466962.0).

EWBF-Miner supports Zcash (ZEC).

### Example usages

Replace `ARCH` for your graphic card architecture. Available option(s): `cuda`

- To run the container in background:

```console
$ docker run -d --device /dev/nvidia0 --device /dev/nvidiactl --device /dev/nvidia-uvm --name YOUR_CONTAINER_NAME calvintam236/ewbf-miner:cuda --algo YOUR_ALGO --server YOUR_POOL_ADDRESS --port YOUR_POOL_PORT --user YOUR_USERNAME.YOUR_WORKER_NAME --pass YOUR_WORKER_PASSWORD
```

- Get `ewbf-miner` options:

```console
$ docker run --rm calvintam236/ewbf-miner:ARCH
```

- To fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```

### Donations

If you like to buy me a cup of coffee for this Dockerfile/ docker image, you can donate to here:

- BTC: `1MTkPFtp3qxE4Y98pTHP3z767RGKmrT92a`
- ETH: `0x5896a85E8c175c563DC00087535582394d394838`
- XMR: `4ASikgNhKqmY5EjnaoDws1jjyhQy9ZrcDcCwfYVt5Rtxb6B1FqsehpLY8ZxxZD5B6r8QZKb4y1FKW1eqiS5Lph77Ca9qprU`
- ETC: `0xFaBA3be3b3De5469C3F6C6185150928F3773C7b4`
- ZEC: `t1Z5Kc75JQ17txyaDUfwwyabTgsJMfuuSp4`
