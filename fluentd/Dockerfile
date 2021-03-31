FROM fluent/fluentd:v1.12.0-debian-1.0
USER root
RUN ["gem", "install", "fluent-plugin-gelf-hs", "--no-document", "--version","1.0.8"]
ADD conf /fluentd/etc
USER fluent