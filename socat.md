# Socat
socat TCP4-LISTEN:9000,fork,reuseaddr,bind=localhost EXEC:"cat /proc/cpuinfo"
