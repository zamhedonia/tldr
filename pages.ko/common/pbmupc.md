# pbmupc

> 범용 상품 코드(UPC)의 PBM 이미지를 생성합니다.
> 더 많은 정보: <https://netpbm.sourceforge.net/doc/pbmupc.html>.

- 지정된 상품 유형, 제조사 코드 및 상품 코드를 위한 UPC 이미지 생성:

`pbmupc {{상품_유형}} {{제조사_코드}} {{상품_코드}} > {{경로/대상/출력.pbm}}`

- 체크섬을 표시하지 않는 대체 스타일 사용:

`pbmupc -s2 {{상품_유형}} {{제조사_코드}} {{상품_코드}} > {{경로/대상/출력.pbm}}`
