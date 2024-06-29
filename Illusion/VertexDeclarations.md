# Illusion Vertex Declarations
- Data are read from resource (Illusion::Buffer).

## Type Table
Name | Size | Description
--- | --- | ---
UBYTE4 | 4 | 4x Byte
UBYTE4N | 4 | 4x Packed Float
UBYTE4_DELTA | 4 | Unknown
BYTE4N | 4 | 4x Packed Float
COLOR4 | 4 | 4x Byte (RGBA)
HALF2 | 4 | 2x Half Float
SHORT4_FIXED4_12 | 8 | Unknown
FLOAT3 | 12 | 3x Float
FLOAT4 | 16 | 4x Float
COLOR4 | 16 | 4x Float

## CloudWisp
```yaml
NameUID: 0xE7CFFC61
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- TexCoord2:
    type: HALF2
    streamNum: 1
- TexCoord3:
    type: HALF2
    streamNum: 1
```

## Decal
```yaml
NameUID: 0x128206B2
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 0
- Normal:
    type: UBYTE4N
    streamNum: 0
- Tangent:
    type: UBYTE4N
    streamNum: 0
```

## Dynamic
```yaml
NameUID: 0x64A43DAE
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 0
- TexCoord1:
    type: HALF2
    streamNum: 0
- Normal:
    type: FLOAT3
    streamNum: 0
- Tangent:
    type: FLOAT3
    streamNum: 0
- Color0:
    type: COLOR4
    streamNum: 0
```

## FBX
```yaml
NameUID: 0xEE711E17
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- Normal:
    type: FLOAT3
    streamNum: 1
- Tangent:
    type: FLOAT3
    streamNum: 1
- Color0:
    type: COLOR4
    streamNum: 1
- BlendIndex:
    type: UBYTE4
    streamNum: 1
- BlendWeight:
    type: UBYTE4N
    streamNum: 1
```

## FBX2
```yaml
NameUID: 0x5589C78D
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- Color0:
    type: COLOR4
    streamNum: 2
- Normal:
    type: FLOAT3
    streamNum: 3
- Tangent:
    type: FLOAT3
    streamNum: 3
- BlendIndex:
    type: UBYTE4
    streamNum: 3
- BlendWeight:
    type: UBYTE4N
    streamNum: 3
```

## GeoParticle
```yaml
NameUID: 0x25586179
RunTimeFlag: 1
IndexStreamMultiplier: 4
IndexStreamAsVertexStream: 1
- Position:
    type: FLOAT3
    streamNum: 0
- Normal:
    type: FLOAT3
    streamNum: 0
- Tangent:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 0
- TexCoord1:
    type: FLOAT4
    streamNum: 1
- TexCoord2:
    type: HALF4
    streamNum: 1
- TexCoord3:
    type: HALF4
    streamNum: 1
- TexCoord4:
    type: FLOAT4
    streamNum: 1
- TexCoord5:
    type: FKIAT3
    streamNum: 1
- TexCoord6:
    type: FLOAT3
    streamNum: 1
- TexCoord7:
    type: HALF4
    streamNum: 1
- BlendWeight:
    type: UBYTE4N
    streamNum: 1
```

## LightCard
```yaml
NameUID: 0x6FA1A436
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord1:
    type: FLOAT4
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 0
- BlendWeight:
    type: UBYTE4N
    streamNum: 0
```

## Lightning
```yaml
NameUID: 0x811776
- Position:
    type: FLOAT3
    streamNum: 0
- Normal:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 0
- Color0:
    type: COLOR4
    streamNum: 0
```

## NC
```yaml
NameUID: 0x34AB04E6
- Position:
    type: FLOAT3
    streamNum: 0
- Normal:
    type: BYTE4N
    streamNum: 1
- Color0:
    type: COLOR4
    streamNum: 1
```

## Particle
```yaml
NameUID: 0xD7A5C4C7
- Position:
    type: FLOAT4
    streamNum: 0
- TexCoord0:
    type: FLOAT4
    streamNum: 1
- TexCoord1:
    type: HALF4
    streamNum: 1
- TexCoord2:
    type: HALF4
    streamNum: 1
- TexCoord3:
    type: FLOAT4
    streamNum: 1
- TexCoord4:
    type: FLOAT3
    streamNum: 1
- TexCoord5:
    type: FLOAT3
    streamNum: 1
- TexCoord6:
    type: HALF4
    streamNum: 1
- BlendWeight:
    type: UBYTE4N
    streamNum: 1
```

## ScreenParticle
```yaml
NameUID: 0x3D339245
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 0
- TexCoord1:
    type: FLOAT4
    streamNum: 0
```

## SkinnedDecal
```yaml
NameUID: 0x23F36527
- Position:
    type: FLOAT4
    streamNum: 0
- Normal:
    type: BYTE4N
    streamNum: 0
- Tangent:
    type: BYTE4N
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 0
```

## Skinned
```yaml
NameUID: 0x276B9567
- Position:
    type: FLOAT4
    streamNum: 0
- Normal:
    type: BYTE4N
    streamNum: 0
- Tangent:
    type: BYTE4N
    streamNum: 0
- BlendIndex:
    type: UBYTE4
    streamNum: 1
- BlendWeight:
    type: UBYTE4N
    streamNum: 1
- TexCoord0:
    type: HALF2
    streamNum: 2
```

## SkinnedUVNT
```yaml
NameUID: 0xAC5D89E2
- Position:
    type: FLOAT4
    streamNum: 0
- Normal:
    type: BYTE4N
    streamNum: 0
- Tangent:
    type: BYTE4N
    streamNum: 0
- BlendIndex:
    type: UBYTE4
    streamNum: 1
- BlendWeight:
    type: UBYTE4N
    streamNum: 1
- TexCoord0:
    type: HALF2
    streamNum: 2
```

## UV2C
```yaml
NameUID: 0x7728A54B
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- Color0:
    type: COLOR4
    streamNum: 1
```

## UV2
```yaml
NameUID: 0x27C88915
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
```

## UV2NC
```yaml
NameUID: 0xF2E6F36B
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- Normal:
    type: BYTE4N
    streamNum: 1
- Color0:
    type: COLOR4
    streamNum: 1
```

## UV2N
```yaml
NameUID: 0x46E52398
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- Normal:
    type: BYTE4N
    streamNum: 1
```

## UV2NTC
```yaml
NameUID: 0x78921EA0
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- Normal:
    type: BYTE4N
    streamNum: 1
- Tangent:
    type: BYTE4N
    streamNum: 1
- Color0:
    type: Color4
    streamNum: 1
```

## UV2NT
```yaml
NameUID: 0xA0B0781E
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- TexCoord1:
    type: HALF2
    streamNum: 1
- Normal:
    type: BYTE4N
    streamNum: 1
- Tangent:
    type: BYTE4N
    streamNum: 1
```

## UVC
```yaml
NameUID: 0xC3BD8945
  - Position:
    type: FLOAT3
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 1
  - Color0:
    type: COLOR4
    streamNum: 1
```

## UVCNPacked
```yaml
NameUID: 0xF0D9B822
  - Position:
    type: HALF4
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 1
  - Normal:
    type: BYTE4N
    streamNum: 1
  - Color0:
    type: COLOR4
    streamNum: 1
```

## UVN
```yaml
NameUID: 0xF2700F96
- Position:
    type: FLOAT3
    streamNum: 0
- TexCoord0:
    type: HALF2
    streamNum: 1
- Normal:
    type: BYTE4N
    streamNum: 1
```

## UVNPacked
```yaml
NameUID: 0x720788F7
  - Position:
    type: HALF4
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 1
  - Normal:
    type: BYTE4N
    streamNum: 1
```

## UVNTC
```yaml
NameUID: 0x911E1A51
  - Position:
    type: FLOAT3
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 1
  - Normal:
    type: BYTE4N
    streamNum: 1
  - Tangent:
    type: BYTE4N
    streamNum: 1
  - Color0:
    type: COLOR4
    streamNum: 1
```

## UVNT
```yaml
NameUID: 0x9BA68DBC
  - Position:
    type: FLOAT3
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 1
  - Normal:
    type: BYTE4N
    streamNum: 1
  - Tangent:
    type: BYTE4N
    streamNum: 1
```

## VehicleGlassUV2NTC
```yaml
NameUID: 0xD08FF31A
  - Position:
    type: FLOAT4
    streamNum: 0
  - Normal:
    type: BYTE4N
    streamNum: 0
  - Tangent:
    type: BYTE4N
    streamNum: 0
  - BlendIndex:
    type: UBYTE4
    streamNum: 1
  - BlendWeight:
    type: UBYTE4N
    streamNum: 1
  - TexCoord0:
    type: HALF2
    streamNum: 2
  - TexCoord1:
    type: HALF2
    streamNum: 2
  - Color0:
    type: COLOR4
    streamNum: 2
```

## VehicleUV2NTC
```yaml
NameUID: 0xBF900E9E
  - Position:
    type: FLOAT4
    streamNum: 0
  - Normal:
    type: BYTE4N
    streamNum: 0
  - Tangent:
    type: BYTE4N
    streamNum: 0
  - BlendIndex:
    type: UBYTE4
    streamNum: 1
  - BlendWeight:
    type: UBYTE4N
    streamNum: 1
  - TexCoord0:
    type: HALF2
    streamNum: 2
  - TexCoord1:
    type: HALF2
    streamNum: 2
```

## VehicleUVNTC
```yaml
NameUID: 0xE234EF7A
  - Position:
    type: FLOAT4
    streamNum: 0
  - Normal:
    type: BYTE4N
    streamNum: 0
  - Tangent:
    type: BYTE4N
    streamNum: 0
  - BlendIndex:
    type: UBYTE4
    streamNum: 1
  - BlendWeight:
    type: UBYTE4N
    streamNum: 1
  - TexCoord0:
    type: HALF2
    streamNum: 2
```

## WaterSurface
```yaml
NameUID: 0xD3798DFD
  - Position:
    type: FLOAT4
    streamNum: 0
  - Normal:
    type: FLOAT4
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 1
```

## MorphTarget
```yaml
NameUID: 0x7029F5BA
  - Position:
    type: UBYTE4_DELTA
    streamNum: 0
  - Normal:
    type: BYTE4N
    streamNum: 0
```

## MultiMorphTarget
```yaml
NameUID: 0x6649E95
  - Position:
    type: SHORT4_FIXED4_12
    streamNum: 0
  - Normal:
    type: BYTE4N
    streamNum: 0
```

## Rain
```yaml
NameUID: 0x48649FC8
  - Position:
    type: FLOAT3
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 0
```

## Slim
```yaml
NameUID: 0x91355905
  - Position:
    type: FLOAT3
    streamNum: 0
```

## SlimUV
```yaml
NameUID: 0x7E0D7533
  - Position:
    type: FLOAT3
    streamNum: 0
  - TexCoord0:
    type: HALF2
    streamNum: 0
```
