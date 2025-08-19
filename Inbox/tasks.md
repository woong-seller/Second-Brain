tasks 플러그인은 체크 박스에 더 많은 기능을 부여하는 플러그인이다. 그리고 그것들을 쿼리문으로 추려서 볼 수 있다. 그래서 일주월년 플래너와 함께 쓰이는게 좋을거 같다. 쿼리문은 

```tasks
```

### 완료되지 않은 일 not done 
### 완료된 일 
- has done date 
- no done date 
- done (on|befor|after) \<date>|\<data range> 
- ### 정렬 
- sort by priority 
- sort by due 
- sort by start 
- sort by scheduled 
- sort by done 
- sort by description 
- sort by path 
- sort by recurring 
- sort by tag 
### 숨김 
- hide start date 
- hide due date 
- hide edit button 
- hide backlink 
### 마감 기한 
- due 2023-12-25
- due before yesterday 
- due today 
- due after 3 days ago 
- due in this week 
- due after this month
- due or or before next year
- due in 2023-Www(ww에는 주, 2자리 숫자) 
- due in 2023-10 (10월) 
- due (before|after|in) \<data range> 
### priority 
- priority is (above|below|not) (lowest|low|none|medium|high|highest) 
- ## Custom filter 
- 
- ### 비어있는 필드 
- 
- #### 비어있는 작업 찾기 description regex matches /^$/ 
- 
- #### 비어있는 작업 제외하기 description regex does not match /^$/ 
- 
- ### 폴더 필터링 
- #### 현재의 폴더에 들어있는 할 일 folder includes {{query.file.folder}} 
- #### 폴더를 포함 filter by function task.file.folder.includes("폴더 이름")
