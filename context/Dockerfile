FROM fluent/fluentd:v1.11-debian-1

USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document"]
RUN ["gem", "install", "fluent-plugin-rewrite-tag-filter", "--no-document"]
RUN ["gem", "install", "fluent-plugin-record-modifier", "--no-document"]

USER fluent


