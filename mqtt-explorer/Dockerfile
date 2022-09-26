FROM smeagolworms4/mqtt-explorer

ENV CONFIG_PATH=/data


CMD node node-server/server/dist/node-server/server/src/index.js \
   --http-port=$HTTP_PORT \
   --config-path=$CONFIG_PATH \
   --http-user=$HTTP_USER \
   --http-password=$HTTP_PASSWORD\
   --ssl-key-path=$SSL_KEY_PATH\
   --ssl-cert-path=$SSL_CERT_PATH
