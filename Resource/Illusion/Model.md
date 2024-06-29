# Illusion::Model

Chunk UID | Type UID
--- | ---
0x6DF963B3 | 0xA2ADCD77

## Data Structure
```yaml
data:
    AABBMin:
        offset: 0x58
        type: Vector3
    NumPrims:
        offset: 0x64
        type: UINT32
    AABBMax:
        offset: 0x68
        type: Vector3
    MaterialTableHandle:
        offset: 0x78
        type: qResourceHandle
    BonePaletteHandle:
        offset: 0x98
        type: qResourceHandle
    MeshOffsetTable:
        offset: 0xB8
        type: INT64
        description: This offset points to array of INT64 with offsets to actual Mesh structure (Illusion::Mesh)
    NumMeshes:
        offset: 0xC0
        type: UINT32
    ModelUser:
        offset: 0xC8
        type: INT64
        description: Offset to Illusion::ModelUser
    LastUsedFrameNum:
        offset: 0xD4
        type: UINT32
    MorphTargetsHandle:
        offset: 0xE8
        type: qResourceHandle
    LocatorsHandle:
        offset: 0x108
        type: qResourceHandle
```
