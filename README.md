# Egypt Siwa Salt Lake - Satellite Imagery Analysis

이집트 시와 소금 호수(Siwa Salt Lake)의 위성 이미지를 분석하는 프로젝트입니다.

## 프로젝트 구조

```
Egypt-Siwa-saltlake/
├── image/          # 위성 원본 이미지 (PNG, TIF)
├── label/          # 분류 라벨 데이터
├── notebooks/      # Jupyter 분석 노트북
└── docs/           # 프로젝트 문서 및 참고자료
```

## 데이터 설명

- **image/**: 위성에서 촬영한 시와 소금 호수 원본 이미지
  - 파일명 형식: `{tile_x}_{tile_y}({class_id}).png / .tif`
- **label/**: 이미지에 대응하는 라벨 데이터

## 분석 노트북

| 노트북 | 설명 |
|--------|------|
| `Egypt_Siwa_saltlake.ipynb` | 위성 이미지 분석 메인 노트북 |

## 시작하기

```bash
pip install numpy pandas matplotlib rasterio jupyter
jupyter notebook
```
