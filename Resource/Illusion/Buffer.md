# Illusion::Buffer

Chunk UID | Type UID
--- |---
0x7A971479 | 0x92CDEC8F

- This is essentially used for mesh data:
  - Indices
  - Vertices
  - Normals
  - Tangents
  - Colors
  - Texture Coords
  - Blend Index
  - Blend Weight
  - Bi Normal

- The game internally calls: https://learn.microsoft.com/en-us/windows/win32/api/d3d11/nf-d3d11-id3d11device-createbuffer

## Data Structure
```yaml
data:
    BufferType:
        offset: 0x58
        type: UINT8
    RunTimeCreated:
        offset: 0x59
        type: UINT8
    Flags:
        offset: 0x5A
        type: UINT16
    DataByteSize:
        offset: 0x5C
        type: UINT32
        description: Size of buffer data.
    Data:
        offset: 0x60
        type: INT64
        description: Offset to buffer data.
    ElementsByteSize:
        offset: 0x68
        type: UINT32
        description: If the elements are only vertices the size would be 0xC (Vector).
    NumElements:
        offset: 0x6C
        type: UINT32
        description: Number of elements.
    BufferUser:
        offset: 0x70
        type: INT64
        description: Offset to buffer user.
    LastUsedFrameNum:
        offset: 0x78
        type: UINT32
```
