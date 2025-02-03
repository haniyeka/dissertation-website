## [My PhD dissertation](https://haniyeka.github.io/dissertation-website/)

### Dissertation Info
* Title: Dynamic Selection of Parallel Portfolio of Algorithms for Solving Combinatorial Problems
* Author: Haniye Kashgarani 
* Advisor: Dr. Lars Kotthoff
* Institution: University of Wyoming 
* Major: Computer Science
* Published: [ProQuest](https://www.proquest.com/docview/3150948537/253E98C17F724BFCPQ/1?accountid=45220&sourcetype=Dissertations%20&%20Theses)

### Built
* Built with [Pandoc](https://pandoc.org/) and [Quarto](https://quarto.org/). 
* Converted Latex format to .qmd with Pandoc chapter by chapter: 

  ```
  pandoc -s chapter.tex -o chapter.qmd --mathjax
  ```
* Rendered to HTML format with Quatro: 
  ```
  quarto render
  ```

