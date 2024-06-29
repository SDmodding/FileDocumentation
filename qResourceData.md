# qResourceData
- This is main structure for each resource that exist in `perm.bin` file.

## Data Structure
```yaml
header:
    ChunkUID:
        offset: 0x00
        type: UINT32
        description: Chunk UID (Inventory UID)
    Size:
        offset: 0x04
        name: mSize
        type: UINT32
        description: Size of Resource.
    Size2:
        offset: 0x08
        type: UINT32
        description: Size of Resource.
    DataOffset:
        offset: 0x0C
        type: UINT32
        description: Offset to qResourceData.

data:
    NameUID:
        offset: 0x18
        type: UINT32
        description: Hash name of the resource name this is essential while game searching for it via inventory.
    TypeUID:
        offset: 0x30
        type: UINT32
        description: Similar to Chunk UID but used for filtering actual type.
    DebugName:
        offset: 0x34
        type: char[36]
        description: Name of the resource, but if the name is too long it is split after 15 character which is represented by the '~' character.
```

## Parsing the perm file with multiple resources
- Header contains size which can be read and offset by size of header to get to next `qResourceData` (mSize + 0x10)
