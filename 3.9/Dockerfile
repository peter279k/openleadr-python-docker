FROM python:3.9

RUN git clone https://github.com/openleadr/openleadr-python \
&& cd openleadr-python \
&& python3 -m venv python_env \
&& ./python_env/bin/pip3 install -e . \
&& ./python_env/bin/pip3 install -r dev_requirements.txt

ENTRYPOINT ["bash"]

CMD ["-c", "cd openleadr-python && source ./python_env/bin/activate"]
