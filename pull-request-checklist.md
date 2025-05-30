# Codewalnut PR Checklist for Front-end Web Application.

## Pull Request standards checklist
- This Branch will be carrying one single responsibility - feature/bugfix/style/refactor...
- I have followed conventional commit messages and descriptive Branch naming.
- My PR has descriptive folder/file names that I have worked on.
- I have attached the Task ticket link in the PR

## Testing checklist
- I have written unit tests for all components files I've worked on, these tests cover what the user sees and how the UI changes when they interact with it.
- I have written unit tests for all helper functions I've worked on, that cover use-cases and edge cases.
- I have written integration tests for features I've worked on, to ensure my components work together as I expect.
- I have checked Sonar Qube quality gate checks for this PR.

### If you have not added tests for any of the above, please explain why below.
...

## Definition of Done

- I have completed the above testing checklist so my code is well tested and I have confidence my code works as I expect in a variety of situations.
- I have Eslint and Prettier enabled to run on file save and I have fixed all errors highlighted by Eslint.
- I have added complete Prop Types and type definitions without using `any` for all my components and helper functions.
- I have deleted all non-descriptive comments and dead code from the files I've touched.
- I have rebased my branch with the base branch I want to merge into and all the commits in this PR are my own.
