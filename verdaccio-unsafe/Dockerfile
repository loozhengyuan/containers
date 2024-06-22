ARG VERDACCIO_VERSION=5.31.1
FROM "verdaccio/verdaccio:${VERDACCIO_VERSION}"

COPY <<EOF /verdaccio/conf/config.yaml
storage: /verdaccio/storage/data
packages:
'@*/*':
    access: \$all
    publish: \$all
'**':
    access: \$all
    publish: \$all
max_body_size: 100mb
log: { type: stdout, format: pretty, level: http }
EOF
