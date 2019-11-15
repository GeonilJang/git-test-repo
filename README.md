### To know about GIT
1. git init
1. git add [ file / . ]
1. git commit -m "commit text"
1. git log ( 커밋정보 확인가능 )
1. git remote add origin url [ url로 원격 저장소로 추가 : origin 원격 저장소의 이름이다 ]
1. git push origin master [ 마스터 브랜치 ]
1. git clone url [ setting / collaborator 추가 해줘야 한다]
<pre>
<code>                             
    [ 작업공간 (내 PC 폴더 ) ] ---------------push--->  [ 원격저장소 ]
        [ 로컬저장소 .git ]
            stage [add 하면 추척 한다 스테이지로 올린다]
            commit [stage에 있는 모든 파일을 커밋 한다 - 파일은 수정 없음 상태로 돌아간다]

    파일수정    add. [stage] 수정없음 --- commit --- push ---> [원격저장소]
    + 파일 생성              파일수정
                             파일생성

</code>
</pre>

1. 브랜치를 생성하자 git branch 이름
1. 브랜치 변경하자 git checkout 이름 1