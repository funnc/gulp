# gulp
백단에 순수 html 파일을 넘길때 작업하는 레포 입니다.


1. npm i
2. gulp 

workspace/index.html 파일은 필수로 있어야 합니다.
소스파일 경로 HTML: './workspace/html',
산출물 경로 HTML: './dist/html',

index.html 파일은 기본적으로 컴파일되며, 

gulpfile.js에 정의된 경로가 아니라면 추적이 안되어 사용시에 경로를 수정하거나 
수동으로 넣어야 합니다

예시)
소스파일 경로
HTML: './workspace/html/cash',
IMAGES: './workspace/assets/images/cash',
산출물 경로
HTML: './dist/html/cash',
IMAGES: './dist/assets/images/cash',

소스파일 경로
HTML: './workspace/html/packing',
IMAGES: './workspace/assets/images/packing',
산출물 경로
HTML: './dist/html/packing',
IMAGES: './dist/assets/images/packing',
