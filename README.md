# mlx4-port-force-eth
init.d script to force all ConnectX-3 VPI (MT27500) ports to run in ethernet mode.

## Install
Copy mlx4-preup to /etc/init.d then run
    chmod +x /etc/init.d/mlx4-preup
    updated-rc.d mlx4-preup defaults
