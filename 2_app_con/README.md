podman build -t app_con .

podman run -it -p 5000:5000 --rm --network host app_con

