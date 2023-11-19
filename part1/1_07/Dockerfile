# Start from the Ubuntu 20.04 image
FROM ubuntu:20.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Copy the curl.sh file from this location to /usr/src/app/ creating /usr/src/app/curl.sh.
COPY curl.sh .

# Add execution rights to the script.
RUN chmod +x curl.sh

# Execute a command with `/bin/sh -c` prefix.
RUN apt update; apt install -y curl

# When running Docker run the command will be ./curl.sh
CMD ./curl.sh
