---
title: SkyData
---
## Description

## Constructors

| Constructor            | Description                                              |
| ---------------------- | -------------------------------------------------------- |
| SkyData()              | Create a new instance of this container type.            |
| SkyData(SkyData other) | Create a reference copy of an instance of the same type. |

## Properties

| Name                             | Type                                             | Description |
| -------------------------------- | ------------------------------------------------ | ----------- |
| cloudLayerSunColor               | [Vec3](/vext/ref/shared/class/vec3)                |             |
| cloudLayer2Color                 | [Vec3](/vext/ref/shared/class/vec3)                |             |
| cloudLayer1Color                 | [Vec3](/vext/ref/shared/class/vec3)                |             |
| skyGradientTexture               | [TextureAsset](/vext/ref/fb/textureasset) |             |
| sunSize                          | number                                           |             |
| brightnessScale                  | number                                           |             |
| sunScale                         | number                                           |             |
| panoramicUVMaxX                  | number                                           |             |
| panoramicUVMinY                  | number                                           |             |
| panoramicUVMaxY                  | number                                           |             |
| realm                            | [Realm](/vext/ref/fb/realm)               |             |
| panoramicUVMinX                  | number                                           |             |
| panoramicTexture                 | [TextureAsset](/vext/ref/fb/textureasset) |             |
| panoramicAlphaTexture            | [TextureAsset](/vext/ref/fb/textureasset) |             |
| panoramicTileFactor              | number                                           |             |
| cloudLayerMaskTexture            | [TextureAsset](/vext/ref/fb/textureasset) |             |
| cloudLayer1Altitude              | number                                           |             |
| cloudLayer1TileFactor            | number                                           |             |
| cloudLayer1Rotation              | number                                           |             |
| cloudLayer1Speed                 | number                                           |             |
| cloudLayer1SunLightIntensity     | number                                           |             |
| panoramicRotation                | number                                           |             |
| cloudLayer1AmbientLightIntensity | number                                           |             |
| cloudLayer1SunLightPower         | number                                           |             |
| cloudLayer1AlphaMul              | number                                           |             |
| cloudLayer1Texture               | [TextureAsset](/vext/ref/fb/textureasset) |             |
| cloudLayer2Altitude              | number                                           |             |
| cloudLayer2TileFactor            | number                                           |             |
| cloudLayer2Rotation              | number                                           |             |
| cloudLayer2Speed                 | number                                           |             |
| cloudLayer2SunLightIntensity     | number                                           |             |
| cloudLayer2SunLightPower         | number                                           |             |
| cloudLayer2AmbientLightIntensity | number                                           |             |
| staticEnvmapScale                | number                                           |             |
| cloudLayer2AlphaMul              | number                                           |             |
| cloudLayer2Texture               | [TextureAsset](/vext/ref/fb/textureasset) |             |
| staticEnvmapTexture              | [TextureAsset](/vext/ref/fb/textureasset) |             |
| skyVisibilityExponent            | number                                           |             |
| skyEnvmap8BitTexScale            | number                                           |             |
| customEnvmapTexture              | [TextureAsset](/vext/ref/fb/textureasset) |             |
| customEnvmapScale                | number                                           |             |
| customEnvmapAmbient              | number                                           |             |
| enable                           | bool                                             |             |

## Methods

| Type                                    | Name            | Parameters |
| --------------------------------------- | --------------- | ---------- |
| [SkyData](/vext/ref/client/class/skydata) | [Clone](#clone) |            |

### Clone

> [SkyData](/vext/ref/client/class/skydata) **Clone**()

Creates a shallow-copy clone of the instance.