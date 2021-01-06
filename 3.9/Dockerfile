FROM python:3.9

RUN git clone https://github.com/openleadr/openleadr-python \
&& cd openleadr-python \
&& pip3 install -e . \
&& pip3 install -r dev_requirements.txt

WORKDIR openleadr-python

ENTRYPOINT ["/bin/bash"]
