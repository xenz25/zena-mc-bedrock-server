# How to use:

- Use the sample-bedrock docker-compose.yaml
    - add the mcworld under the world folder and named it `world.mcworld`
    - You can define some environment variables under the .env for quick editing, this values overrides the one defined in the docker-compose yaml environments section.

- To run it you need docker or podman. Run this command on a terminal pointing to the directory where you docker compose is located
```cmd
docker compose up -d
```

- Note this requires a udp forwarder service so devices can connect to the udp port you forward on the docker compose yaml.
    - You can use the one I created here: [duplex-udp-forwarder-service](https://github.com/xenz25/duplex-udp-forwarder-service/tree/main)

# Related references:
- [docker-minecraft-bedrock-server](https://github.com/itzg/docker-minecraft-bedrock-server)