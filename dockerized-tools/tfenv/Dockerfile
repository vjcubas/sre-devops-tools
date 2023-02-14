FROM alpine:3.17

RUN apk add --no-cache git
RUN git clone --depth=1 https://github.com/tfutils/tfenv.git ~/.tfenv
RUN echo 'export PATH="$HOME/.tfenv/bin:$PATH"' >> ~/.bash_profile

ENTRYPOINT ["bash"]