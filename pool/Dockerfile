FROM inputoutput/cardano-node

# Change 3201 below and further below to your port number

EXPOSE 3201

ENTRYPOINT ["/bin/bash", "-c", "cardano-node run \
--topology /config/relay_topology.json \
--database-path /db \
--socket-path /ipc/node.socket \
--host-addr 0.0.0.0 \
--port 3201 \
--config /opt/cardano/config/mainnet-config.json \
--shelley-kes-key /config/kes.skey \
--shelley-vrf-key /config/vrf.skey \
--shelley-operational-certificate /config/node.cert"]
