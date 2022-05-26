FROM danchitnis/xrdp:ubuntu-xfce

# chrome dependencies
RUN apt-get update && apt-get install -yq  fonts-liberation xdg-utils
RUN wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb \
&& dpkg -i google-chrome-stable_current_amd64.deb