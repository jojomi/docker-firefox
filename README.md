# docker-firefox

Docker container for isolated up-to-date firefox


## Build

    docker build -t jojomi/firefox .


## Run

    docker run -it --rm --volume "$(pwd)/output:/output" jojomi/firefox --headless --screenshot /output/google.png google.com
