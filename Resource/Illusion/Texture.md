# Illusion::Texture

Chunk UID | Type UID
--- |---
0xCDBFA090 | 0x8B43FABF

## Data Structure
```yaml
data:
    Flags:
        offset: 0x58
        type: UINT32
        description: Mask flags
    Format:
        offset: 0x5C
        type: UINT8
        description: Format type which the texture is compressed with.
    Type:
        offset: 0x5D
        type: UINT8
        description: Type of the texture.
    Aniso:
        offset: 0x5E
        type: UINT8
    MipMapBiasPreset:
        offset: 0x5F
        type: UINT8
    MipMapBias:
        offset: 0x60
        type: UINT32
    Width:
        offset: 0x64
        type: UINT16
        description: Width of the texture.
    Height:
        offset: 0x66
        type: UINT16
        description: Height of the texture.
    NumMipMaps:
        offset: 0x68
        type: UINT8
    Filter:
        offset: 0x69
        type: UINT8
    Depth:
        offset: 0x6A
        type: UINT16
    AlphaStateUID:
        offset: 0x6C
        type: UINT32
        description: Name hash of alpha state.
    TextureUser:
        offset: 0x70
        type: INT64
        description: Offset to Texture User.
    ImageDataByteSize:
        offset: 0x78
        type: UINT32
        description: Size of the texture data in 'temp.bin' file.
    LastUsedFrameNum:
        offset: 0x7C
        type: UINT32
    ImageDataPosition:
        offset: 0x78
        type: UINT64
        description: Offset to texture data in 'temp.bin' file.
```

## Filter
```cpp
enum Illusion::Texture::Filter
{
    FILTER_DEFAULT = 0x0,
    FILTER_LINEAR = 0x1,
    FILTER_POINT = 0x2,
    FILTER_ANISOTROPIC = 0x3,
    FILTER_CONVOLUTION = 0x4
};
```

## Flags
```cpp
enum Illusion::Texture::Flags
{
    FLAG_CLAMPU = 0x1,
    FLAG_CLAMPV = 0x2,
    FLAG_MIRRORU = 0x4,
    FLAG_MIRRORV = 0x8,
    FLAG_LINEAR = 0x100,
    FLAG_LE = 0x200,
    FLAG_CPU_WRITABLE = 0x400,
    FLAG_TARGET = 0x800,
    FLAG_PS3_TARGET_TILED = 0x1000,
    FLAG_IN_INVENTORY = 0x2000,
    FLAG_CREATED_AT_RUNTIME = 0x4000,
    FLAG_MOVING = 0x8000,
    FLAG_NO_EXPAND_AS_16 = 0x10000,
    FLAG_MOVIE_TEXTURE = 0x20000,
    FLAG_CPU_READABLE = 0x40000,
    FLAG_MIPS_SHADER_SRC = 0x80000,
    FLAG_PRESENT_BUFFER = 0x100000,
    FLAG_ALIASED_TEXTURE = 0x200000,
    FLAG_PC_MAIN_MEM_COPY = 0x400000,
    FLAG_PC_UNORDERED_ACCESS = 0x800000,
    FLAG_REBIND_DATAHANDLE = 0x1000000,
    FLAG_XB1_USE_ESRAM = 0x2000000,
    FLAG_MSAA_2X = 0x4000000,
    FLAG_MSAA_4x = 0x8000000,
    FLAG_SAMPLER_ADDRESS_MASK = 0xF,
    FLAG_RUNTIME_MASK = 0x100A000
};
```

## Format
```cpp
enum Illusion::Texture::Format
{
    FORMAT_A8R8G8B8 = 0x0,
    FORMAT_DXT1 = 0x1,
    FORMAT_DXT3 = 0x2,
    FORMAT_DXT5 = 0x3,
    FORMAT_R5G6B5 = 0x4,
    FORMAT_A1R5G5B5 = 0x5,
    FORMAT_X8 = 0x6,
    FORMAT_X16 = 0x7,
    FORMAT_CXT1 = 0x8,
    FORMAT_DXN = 0x9,
    FORMAT_BC6H_UF16 = 0xA,
    FORMAT_BC6H_SF16 = 0xB,
    FORMAT_BC7_UNORM = 0xC,
    FORMAT_BC7_UNORM_SRGB = 0xD,
    FORMAT_R32F = 0xE,
    FORMAT_X16FY16FZ16FW16F = 0xF,
    FORMAT_D24S8 = 0x10,
    FORMAT_D24FS8 = 0x11,
    FORMAT_SHADOW = 0x12,
    FORMAT_DEPTHCOPY = 0x13,
    FORMAT_A2R10G10B10 = 0x14,
    FORMAT_A2R10G10B10F = 0x15,
    FORMAT_A16B16G16R16 = 0x16,
    NUM_TEX_FORMATS = 0x17
};
```

## Type
```cpp
enum Illusion::Texture::Type
{
    TYPE_2D = 0x0,
    TYPE_3D = 0x1,
    TYPE_CUBE = 0x2,
    TYPE_2D_ARRAY = 0x3,
    NUM_TEX_TYPES = 0x4
};
```
