* 게시판 기능
  * 등록하기 (Robin)
  * 수정하기
    * 자신이 등록한 글만 수정할 수 있습니다.
    * 게시글을 ID (PK) 가 바뀌어서는 안됩니다. (Create 가 아니라 Update 가 이루어져야함)
  * 삭제하기
    * 실제로 삭제하지 않고 isDel flag 를 두어 처리한다.
    * 자신이 등록한 게시글만 삭제한다.
  * 목록보기
    * 페이징 기능이 있어야 한다.
    * Title 로 검색이 가능해야 한다.
  * 상세보기
    * 삭제된 게시글을 조회할 수 없다.

* 덧글 기능
  * 등록하기
    * 대댓글 개념이 있어야 한다.
  * 수정하기
    * 자신이 등록한 글만 수정할 수 있습니다.
  * 삭제하기
    * 자신이 등록한 글만 수정할 수 있습니다.
  * 전체보기
    * 대댓글 개념을 적용해야 함.
    * sort 는 날짜별로 오름차순으로 하되, 대댓글은 상위댓글 바로 아래 나오도록 설정.
    
* MyPage 기능
  * 쪽지 기능
    * 발송하기
      * 상대ID 로 쪽지를 보낼 수 있다.
      * 존재하지 않는 ID로 쪽지를 보낼경우 지정된 오류를 리턴한다.
    * 삭제하기
      * 자신이 받은 쪽지만 삭제할 수 있다.
      * 삭제는 여러개를 동시에 할 수 있다.
    * 목록보기
      * 내가 받은 모든 쪽지 목록을 볼 수 있다.
      * 페이징 기능이 들어가야 한다.
    * 발신함 보기
      * 내가 보낸 쪽지를 볼 수 있다.       
    * 상세보기
      * 삭제한 쪽지는 조회할 수 없다.
    * 알림기능
      * 읽지 않은 쪽지의 갯수를 확인할 수 있다.
    
