FROM circleci/python:2.7
RUN wget http://picat-lang.org/download/picat22_linux64.tar.gz -O /tmp/picat22_linux64.tar.gz \
         && tar zxvf /tmp/picat22_linux64.tar.gz -C /tmp --no-same-owner \
         && sudo mv /tmp/Picat/picat /usr/bin