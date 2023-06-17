*commit*
   git add README.txt      -> 커밋에 추가할 파일 선택
   git commit -m "커밋에 대한 설명"    -> 커밋에 대한 설명

*checkout*
   git log -> 지금까지 만든 커밋 확인
   git checkout OOOOOOO -> 커밋 앞7자리 문자, 해당 커밋으로 돌아감
   git checkout -  -> 최근 커밋으로 돌아감

*push* 
   git remote add origin 레포지토리 주소 ->레포지토리 주소 넣기
   git push origin master ->커밋들을 레포지토리에 올리기

*clone*
   git clone 레포지토리 주소 . ->새로운(?) 폴더에 레포지토리 커밋을 내려받기 (맨 마지막에 띄우고 마침표 찍기)

*pull*
   git pull origin master -> 레포지토리의 새 커밋을 로컬 저장소에 갱신하기
 