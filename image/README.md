# Image

위성에서 촬영한 이집트 시와 소금 호수 원본 이미지 파일입니다.

## 파일명 형식

```
{tile_x}_{tile_y}({class_id}).png
{tile_x}_{tile_y}({class_id}).tif
```

- `tile_x`, `tile_y`: 위성 타일 좌표
- `class_id`: 분류 클래스 ID
- `.png`: 시각화용 이미지
- `.tif`: 분석용 GeoTIFF 원본 (`.gitignore`에 의해 git 추적 제외)
