# rmslickquiz

Working example for embedding a quizzes into a static R Markdown HTML document/website, using the slick quiz jquery library [https://github.com/jewlofthelotus/SlickQuiz](https://github.com/jewlofthelotus/SlickQuiz)

1. Download repo as a .zip
2. open the `quizRmarkdown.Rproj`
3. open testQuiz.Rmd, knit, you should see the example quiz working
4. Edit the yaml in quizzes/quizyaml/quiz1.yml to change the quiz

The slickQuiz plugin has many different options and formats that I haven't explored, but they are in the readme on the slickquiz repo.


## some nice features

1. small footprint on site
2. roll through multiple questions in the same code block
3. write feedback for each question
4. it auto-grades and displays results, along with any additional feedback at the end

Note: slickquiz is really a .js animal. This is just a little trick to write the quizzes in yaml, which is nicer to write in then JSON, and then put them in an R markdown document.

## unknowns

1. haven't tried putting more than one quiz block into a document, looks like some code will need to be modified for that

## interesting ideas

1. pair with firebase and save all the quiz answers easily.
2. Maybe improve on not having to write in yaml for the quizzes...At least for a common quiz, I might make a small quiz language for humans.



