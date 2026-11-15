# 서체·내장 자료 고지

## Paperlogy로 선언된 서체

실행 HTML은 Paperlogy 이름으로 굵기 400·600·700의 폰트 데이터 3종을 포함합니다. HTML 안의 `paperlogy-license` 고지 원문을 [licenses/OFL-Paperlogy.txt](licenses/OFL-Paperlogy.txt)에 그대로 복사했습니다. 실행 파일 안의 고지도 보존했습니다.

HTML 고지에는 `Copyright 2024 The PAPERLOGY Authors`와 SIL Open Font License 1.1이 기재되어 있습니다. 600 TTF의 내부 메타데이터에서는 `Paperlogy 6 SemiBold`, `Copyright © 2024 PT&` / `Copyright © 2024 피티앤`, OFL 1.1 문구를 확인했습니다. 두 출처의 표기를 구분해 기록했으며 원래 고지나 폰트 파일을 수정하지 않았습니다. 400·700 WOFF2의 내부 이름 테이블은 이번에 직접 검사하지 않았습니다. 원 배포본과의 최종 대조는 확인표에 남겨 두었습니다.

HTML에 기록된 서체 안내 주소: https://freesentation.blog/paperlogy

## 이미지·일러스트

이미지 데이터 62개가 HTML에 포함되어 있습니다. 키·형식·크기·해시는 [내장 자료 목록](docs/ASSET_INVENTORY.md)에 기록했습니다. 현재 표시되지 않는 잔존 자료도 파일과 함께 배포되므로 목록에서 제외하지 않았습니다. 이미지의 원출처·생성/제작 경위·공개 허락은 파일 안의 데이터만으로 확인할 수 없었습니다.

이 준비 작업에서 이미지를 추출해 별도 파일로 배포하거나 권한 상태를 확인 완료로 바꾸지 않았습니다. 원본·계약·배포 조건·생성 이력 등의 자료로 공개 범위를 확인해야 합니다.

## 실행 코드 의존성

현재 HTML에서 외부 실행 스크립트를 불러오는 `script src`는 발견되지 않았습니다. 모델은 포함된 JavaScript 및 브라우저 WebGL/SVG API로 표시됩니다. 이 사실이 프로젝트 코드나 이미지 전체의 권한 확인을 대신하지는 않습니다.
