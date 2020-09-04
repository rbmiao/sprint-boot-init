# Spring Boot Lazy Initialization example

## Versions Used
- Spring Boot - 2.2.0-M1
- H2 Database - 1.4.197

## Configuration
`spring.main.lazy-initialization` is set to `false` by default. This can be set to `true` to enable Lazy Initialization in the Spring Boot Project.

## Alternatives
- `http://localhost:8080/lazy` - Uses `LazyController` and `LazyService` which can be marked manually as `@Lazy` for specific Beans

## Creating a repo on github.com
- echo "# sprint-boot-init" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M master
- git remote add origin https://github.com/rbmiao/sprint-boot-init.git
- git push -u origin master
