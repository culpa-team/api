# CULPA API
This is a RESTful API written for CULPA. Please use it to make awesome things! We reserve all rights to the data.

# API Documentation

## Courses `/courses`
Course by ID - `/courses/course_id/<course_id>`

Courses by Search - `/courses/search/<search_query>`

Courses by Department - `/courses/department_id/<department_id>`

## Departments `/departments`
Department by ID - `/departments/department_id/<department_id>`

Departments by Search - `/departments/search/<search_query>`

Departments by Professor - `/departments/professor_id/<professor_id>`

## Professors `/professors`
Professor by ID - `/professors/professor_id/<professor_id>`

Professors by Search - `/professors/search/<search_query>`

Professors by Department - `/professors/department_id/<department_id>`

Silver Nugget Professors - `/professors/silver_nuggets`

Gold Nugget Professors - `/professors/gold_nuggets`

## Reviews `/reviews`
Review by ID - `/reviews/review_id/<review_id>`

Reviews by Professor - `/reviews/professor_id/<professor_id>`

Reviews by Course - `/reviews/course_id/<course_id>`
