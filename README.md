## TASK 2
#### [Writing test cases](https://drive.google.com/drive/folders/1ewe3GRuz7xAmlcNco45YH7otxaJhBYIw?usp=share_link)
* Subtask 1 - [Test cases based on given user stories](https://docs.google.com/spreadsheets/d/1VQhZB25Bu_mkIA3bUa-YirgFrkUKb9kJQVJUOcepW0Q/edit?usp=share_link)
* Subtask 2 - [Test cases invented by me](https://docs.google.com/spreadsheets/d/1VQhZB25Bu_mkIA3bUa-YirgFrkUKb9kJQVJUOcepW0Q/edit?usp=share_link)
* Subtask 4 - [Group work on test cases](https://docs.google.com/spreadsheets/d/1VgJt98b6bYua1-8JfPPsxL6sXEJKsAZaQiAxdqr93Bk/edit?usp=share_link)
#### Subtask 3 - Why do we write test cases?

## TASK 1
#### Subtask 1
`9/10`
#### Subtask 3
I have decided to participate in this challange, because I liked the idea of creating portfolio during the course. I already had theoretical knowledge in manual testing field, but I was looking for opportunity to challenge myself in practical area. 

I hope this course will help me build strong practical skills and give me an extra advantage, while I will be looking for new, dream job.
#### Subtask 4 - [Application](https://scouts-test.futbolkolektyw.pl/) exploratory test
> 1. What is this application for?

It's an application for football scouts, that helps tracking players factors, matches and results. 
> 2. What functionality the application has? 
- Adding players,
- Adding reports,
- Adding matches, 
- Editing all above,
- Checking players list (user can filter it and print chosen records). 
> 3. What do you think about application's interface? 
- It is very simple and not contemporary,
- It is pretty legible, but not attractive.
> 4. Do you find this application intuitive?
- It has small amount of functionality, but it makes it readable,
- Not intuitive aspects of application:
  - Most of options are hidden rather than displayed on the main menu,
  - There is no signals, that user can open player's profile directly from players list, 
  - User can open matches only from players list,
  - User cannot open report, he can only edit it, 
  - User cannot add a new player directly from players list, only from Main Page,
  - There is no matches and reports lists, 
  - Creating report looks difficult and there is no instruction for it.
> 5. Did you find some issues?
- In "Add player" form:
  * User can enter wrong data in fields (e.g. email address without `@`, `01/01/0001` as day of birth or number in the name),
  * User can add empty fields with languages and YT links, 
- User can't see that he can open player's profile from players list until he clicks (hover state is not presented),
- In polish translation: 
  - On Main Page `Dev team contact` link is not translated,
  - In Players list additional options like `print`, `filter`, etc. stayed in english,
  - There should be `liczba` (number) instead of `ilość` (quantity) in players, matches, reports and actions count,
  - There is mistake in phraze `Matches count` - should be `meczów`.
