Dockerfile to build fluentbit sidecar.

Its used for tailing log file from application and send it to elasticsearch.
Expects log file to be in json (although you can create a parser and accept other format, but 2 lazy for that)

