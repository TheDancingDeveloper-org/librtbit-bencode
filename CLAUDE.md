# librtbit-bencode

Bencode serialization and deserialization using Serde.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |
| librtbit-core (lib) | git | v0.1.0 |
| librtbit-peer-protocol (lib) | git | v0.1.0 |
| librtbit-dht (lib) | git | v0.1.0 |
| librtbit-tracker-comms (lib) | git | v0.1.0 |

### Depends On

- **librtbit-buffers** (git, v0.1.0) — for ByteBuf/ByteBufOwned types
- **librtbit-clone-to-owned** (git, v0.1.0) — for CloneToOwned trait

## Public API

- `BencodeDeserializer` — Serde deserializer for bencode format
- `bencode_serialize_to_writer` — Serde serializer for bencode format
- `BencodeValue` — dynamic bencode value type
- `raw_value` — raw bencode value handling
