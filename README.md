# docker-2048

simple is better

a smaller docker version of 2048

Base on gabrielecirulli/2048(https://github.com/gabrielecirulli/2048)

Base on CentOS Streasm 9

Base on nginx

# run the docker container with your own build

    git clone https://github.com/amoralej/game2048.git
    buildah bud -t game2048 game2048
    podman run --rm -dt -p8080:80/tcp localhost/game2048:latest
    podman run --pull=always -dt -p8080:80 quay.io/amoralej/game2048:latest
# run the podman container by pulling the image directly


# Access the game

    http://127.0.0.1:8080

