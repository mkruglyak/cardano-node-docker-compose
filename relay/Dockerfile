FROM inputoutput/cardano-node

# Change 3101 below and further below to your port number

EXPOSE 3101

ENTRYPOINT ["/bin/bash", "-c", "cardano-node run \
--topology /config/pool_and_peers_topology.json \
--database-path /db \
--socket-path /ipc/node.socket \
--host-addr 0.0.0.0 \
--port 3101 \
--config /opt/cardano/config/mainnet-config.json"]
