FROM mongo:3.6.2

HEALTHCHECK --interval=10s --retries=2 --start-period=15s --timeout=5s CMD mongo --eval "db.runCommand('ping').ok"
