# interview-list-study


## **참고 인터뷰 리스트**

### [Sirloin Dev](https://github.com/sirloin-dev/meatplatform/blob/master/job-description/interview-questions.adoc)
### [Interview_Question_for_Beginner](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)
### [Backend-Interview-Question](https://github.com/ksundong/backend-interview-question)
### [tech-interview-for-developer](https://github.com/gyoogle/tech-interview-for-developer)

***

## `Link`

```
- 이름 [주제이름](링크)
```



## `git`
git 참고 링크
### [git](https://livecoding.tistory.com/19)

```
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir Desktop % cd interview-list-study 
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git branch
* main
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git branch jhj
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git branch -v
  jhj  1dbb8bc Merge pull request #2 from jdalma/chr
* main 1dbb8bc Merge pull request #2 from jdalma/chr
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git checkout jhj
'jhj' 브랜치로 전환합니다
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git branch -v
* jhj  1dbb8bc Merge pull request #2 from jdalma/chr
  main 1dbb8bc Merge pull request #2 from jdalma/chr


jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git status
현재 브랜치 jhj
커밋하도록 정하지 않은 변경 사항:
  (무엇을 커밋할지 바꾸려면 "git add <파일>..."을 사용하십시오)
  (use "git restore <file>..." to discard changes in working directory)
        수정함:        README.md

커밋할 변경 사항을 추가하지 않았습니다 ("git add" 및/또는 "git commit -a"를
사용하십시오)
```

## `git push`

```
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git add .
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git commit -m "git 추가" 
[jhj b2d9c7e] git 추가
 1 file changed, 18 insertions(+)
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git push
fatal: 현재 브랜치 jhj에 업스트림 브랜치가 없습니다.
현재 브랜치를 푸시하고 해당 리모트를 업스트림으로 지정하려면
다음과 같이 하십시오.

jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git push
fatal: 현재 브랜치 jhj에 업스트림 브랜치가 없습니다.
현재 브랜치를 푸시하고 해당 리모트를 업스트림으로 지정하려면
다음과 같이 하십시오.

    git push --set-upstream origin jhj

jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % git push --set-upstream origin jhj
오브젝트 나열하는 중: 5, 완료.
오브젝트 개수 세는 중: 100% (5/5), 완료.
Delta compression using up to 8 threads
오브젝트 압축하는 중: 100% (2/2), 완료.
오브젝트 쓰는 중: 100% (3/3), 678 bytes | 678.00 KiB/s, 완료.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/jdalma/interview-list-study.git
   1dbb8bc..b2d9c7e  jhj -> jhj
'jhj' 브랜치가 리모트의 'jhj' 브랜치를 ('origin'에서) 따라가도록 설정되었습니다.
jeonghyeonjun@jeonghyeonjun-ui-MacBookAir interview-list-study % 
```
