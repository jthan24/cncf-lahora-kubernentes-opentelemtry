podman build -t app_sin .

podman run -it -p 5000:5000 --rm --network host app_sin

