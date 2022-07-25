# GuestBook
| Method | URI | Description |
| --- | --- | --- |
| Get | /guestbook/list | 리스트 조회 |
| Post | /guestbook/register | 방명록 남기기 |
| Get | /guestbook | redirect : /guestbook/list |
| Post | /guestbook/remove | 방명록 삭제 |
| Get | /guestbook/read | 방명록 읽기 |
| Post | /guestbook/modify | 방명록 수정 |
| get | /guestbook/list | 검색기능 |
| Get | /guestbook/list(page= ${result.end + 1} | 다음 페이지 |
| Get | /guestbook/list(page= ${result.start -1} | 이전 페이지 |

test good