# 2023_OSS

## 2023 OSS 수업

---

### 3주차 git

### 이미지

![한국항공대학교_로고](../img/한국항공대학교_로고.png "한국항공대학교")

### 링크
[LMS](https://lms.kau.ac.kr/)

### ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2)

### 주요 git 명령어
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
    * 예) git add
* commit
* git reset HEAD : stage된 파일을 unstaged로 변경
* git checkout -- : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림
* branch
* merge
* status
* log
    * 예) git log --oneline --decorate --graph --all

---

## 2주차 숙제
```
$name = "박준규"
$student_id = "2021125027"
$file_path = `find /home/kau2/ -name w2_homework.txt 2> /dev/null`
$line_num = `wc -l $file_path | cut -c 1 -`

#!/usr/bin/env bash
echo "----------"
echo "name : $name"

echo

echo "----------"
echo "student id : $student_id"



echo "----------"
echo
echo "file path : $file_path"
echo


echo "----------"
echo "line number : $line_num"
echo

echo "----------"
echo "lask line :"
tail -n 1 $file_path
```

# 마크다운

### 목록

**번호 있는 목록 : 내림차순 정렬**

1. 첫번째
2. 세번째
3. 두번째

**번호 없는 목록 : \*,-,+**
* 첫번째
* 세번째
* 두번째

---

+ 빨강
    + 녹색
        + 파랑

**강조**

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

~~cancelline~~
