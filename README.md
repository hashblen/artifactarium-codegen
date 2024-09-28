# artifactarium_codegen

need to update types for [artifactarium](https://github.com/hashblen/artifactarium-codegen)?
- create `data` directory with following structure
  - PacketHead Proto -> `./data/proto/PacketHead.proto` 
  - protos -> `./data/proto/*.proto`
  - packetIds.json -> `./data/packetIds.json`
- `cargo run -- <path to reliquary lib dir> <path to data dir>`