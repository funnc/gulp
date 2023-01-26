# gulp
백단에 순수 html 파일을 넘길때 작업하는 레포 입니다.

파일의 로그관리, 소스관리 등을 위하여 생성되었습니다.

1. npm i
2. gulp 

workspace/index.html 파일은 필수로 있어야 합니다.
소스파일 경로 HTML: './workspace/html',
산출물 경로 HTML: './dist/html',

index.html 파일은 기본적으로 컴파일되며, 

gulpfile.js에 정의된 경로가 아니라면 추적이 안되어 사용시에 경로를 수정하거나 
수동으로 넣어야 합니다. 
( ※ 경로 수정하고 gulp 쳤을때 계속 로딩중인 화면이 나오거나 흰화면이 나올때 놀라지 마시고 필요한 경로로 이동하기 )

백엔드에게 넘길때는 폴더 구조가 이 프로젝트와 sync가 맞지 않기 때문에 별도로 전달하여야 합니다..

예시)
소스파일 경로

HTML: './workspace/html/cash',

IMAGES: './workspace/assets/images/cash',

STYLE: './workspace/assets/style/cash',


산출물 경로

HTML: './dist/html/cash',

IMAGES: './dist/assets/images/cash',

STYLE: './dist/assets/style/cash',

소스파일 경로
HTML: './workspace/html/packing',

IMAGES: './workspace/assets/images/packing',

STYLE: './workspace/assets/style/packing',


산출물 경로

HTML: './dist/html/packing',

IMAGES: './dist/assets/images/packing',

STYLE: './dist/assets/style/packing',
