#유닛에서 모형을 내보내기

###### *version :2.0.2beta   Update:2019-4-26 插件版本:2.0.2*

앞[Unity插件篇](http://localhost/LayaAir2_Auto/%E5%9C%B0%E5%9D%80)간단한 플러그인을 사용하여 요정을 내보내는 요정을 상세하게 설명할 것입니다.

*여기 원숭이 모형을 사용해서 예로 하겠습니다.*

[] (img/1.png)<br>(1)

원숭이 모형 파일 구조를 보도록 하겠습니다.

[] (img/2.png)<br>(2)

선택`预设`그리고 클릭`导出`원숭이 모형을 내보내다.

[] (img/3.png)<br>(2)

내보내기 후 파일 디렉터리가 아래와 같이 표시됩니다:

[] (img/4.png)<br>(4)

####*.lh 형식 데이터 파일

`*.lh`내보내는 3D 디스플레이 용기 Spirte3D 형식 데이터 파일, JSON 형식 인코딩, 유닛y3D 내보내기 플러그인 내보내기 플러그인 선택**미리 설치하다**유형 생성, 내용은 *.ls 격식보다 빛사진 스티커가 없어지고 다른 모든 것이 똑같습니다.

####*.lm 형식 데이터 파일

내보내든**장면 파일**혹은**예설 파일**형식, 내보내는 자원 폴더에는 시리즈 *.lm 형식 파일이 포함되어 있습니다. 이 항목 중`LayaMonkey`폴더는 유닛에서 개발자가 만든 FBX 모형 폴더를 저장하는 폴더로, 그림 4, 내보내는 폴더와 lm 자원 파일을 생성했습니다.

`*.lm`파일은 모형의 격자 데이터 파일이다.Meshsprite 3D나 SkinedMeshsprite3D 형식을 나타낼 수 있는 메쉬(메쉬), 파일에는 모형 네일 칸의 정점 위치, 법선, 정점 UV 등 정보가 포함되어 있다.

####*lav 형식 데이터 파일

`*.lav`서류는 복피 골격 애니메이션 데이터 파일이다.SkinedMeshsprite3D 복피 격요정을 생성할 수 있는 Avatar (뼈).

서류에 골격 노드 정보가 포함되어 있다.

####*.lmat 형식 데이터 파일

`*.lmat`서류는 소재 데이터 파일.모형을 생성할 수 있는 material (소재).소재 스티커, 소재 볼 색상 정보, 컬러 정보, 텍스처 정보 등 소재 관련 정보가 포함되어 있습니다.

> 더 많은 자원 유형들은 자원 개술편의 자원 유형 설명[地址](https://ldc2.layabox.com/doc/?nav=zh-js-4-3-0)차다