# git-use-in-sts

2022-11-22
문제 : sts에서 git 연동 후 unstaged change에서 파일들은 안보이고 git repository모양만 보였다.
처음엔 이 자체를 commit하면 되는가 싶어서 add selected files to index를 했지만 아무리 클릭해도 staged change로
설정 되지 않았다.
그래서 git을 새로 만들어 보기도 하고 검색해봤지만 아무리해도 방법은 나오지 않아서 sts에서 답을 찾기로 했다.

해결 방법 : 해당  unstaged change에서 repository모양 아이콘에 show in 클릭 후 git repositories 클릭하면 변경된 파일들이 나온다.
그 파일들을 +버튼 누른후 push하면 git에 commit된것을 볼 수 있다.