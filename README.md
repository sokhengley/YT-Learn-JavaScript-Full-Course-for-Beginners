# Learning and Practicing Workflow

1. Lesson from YouTube: [Learn JavaScript - Full Course for Beginners](https://www.youtube.com/watch?v=PkZNo7MFNFg)
2. Each chapter we create git branch

```shell
>git checkout -b {chapter_title}
```

**Ex:** our first chapter title is ["Running JavaScript"](https://www.youtube.com/watch?v=PkZNo7MFNFg&t=84s), so we create git branch as below:

```shell
>git checkout -b 01-Running-JavaScript
```

3. Then we can practise code by follow the chapter content of the video.
4. After complete each chapter, we need to commit code and create new branch for new chapter.

```shell
>git add {file_name_1} {file_name_2}
>git commit -m "input your comments here"
>git push origin {branch_name}
>git checkout -b {chapter_title}
```

**Ex:** we already completed chapter 1, and the title for chapter 2 is ["Comment Your Code"](https://www.youtube.com/watch?v=PkZNo7MFNFg&t=263s), so our commands should be:

```shell
>git add index.html
>git commit -m "completed chapter #1"
>git push origin 01-Running-JavaScript
>git checkout -b 02-Comment-Your-Code
```


_Happy Learning..._
