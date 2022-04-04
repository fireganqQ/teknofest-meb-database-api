# Login
## Login
```url
 {url}/api/v1/<auth_token>/<school_code>/login/
```

# Read
## Retrieving Class Data
```url
 {url}/api/v1/<auth_token>/<school_code>/login/read/<_class>/
```

# Push
## Creating the School's Classes
```url
 {url}/api/v1/<auth_token>/<school_code>/login/push/classes/<classes>
```
 - ```classes```: All Classes

### Use
 - ```<branch_number>=<branch_name>```: Specify "=" Between Class Number and Class Name
 - ```branch_number>=<branch_name>&<branch_number2>=<branch_name2>```: Add "&" Between Class Information


## Entering the Class Schedule
```url
 {url}/api/v1/<auth_token>/<school_code>/login/push/class_data/<class>/<lessonId>/<day1>/<day2>/<day3>/<day4>/<day5>/<day1Teacher>/<day2Teacher>/<day3Teacher>/<day4Teacher>/<day5Teacher>/
```
 - ```/class```: Class Number and Class Name (Without Spaces)
 - ```/lessonId```: How Many Lessons Is It?
 - ```/day1```: Day 1 x. lesson
 - ```/day2```: Day 2 x. lesson
 - ```/day3```: Day 3 x. lesson
 - ```/day4```: Day 4 x. lesson
 - ```/day5```: Day 5 x. lesson
 - ```/day1Teacher```: Day 1 x. Teacher of the Course
 - ```/day2Teacher```: Day 2 x. Teacher of the Course
 - ```/day3Teacher```: Day 3 x. Teacher of the Course
 - ```/day4Teacher```: Day 4 x. Teacher of the Course
 - ```/day5Teacher```: Day 5 x. Teacher of the Course


# Update
## Updating the Class Schedule
```url
 /api/v1/<auth_token>/<school_code>/login/update/class_data/<class>/<lessonId>/<day1>/<day2>/<day3>/<day4>/<day5>/<day1Teacher>/<day2Teacher>/<day3Teacher>/<day4Teacher>/<day5Teacher>/
```
 - ```/class```: Class Number and Class Name (Without Spaces)
 - ```/lessonId```: How Many Lessons Is It?
 - ```/day1```: Day 1 x. lesson
 - ```/day2```: Day 2 x. lesson
 - ```/day3```: Day 3 x. lesson
 - ```/day4```: Day 4 x. lesson
 - ```/day5```: Day 5 x. lesson
 - ```/day1Teacher```: Day 1 x. Teacher of the Course
 - ```/day2Teacher```: Day 2 x. Teacher of the Course
 - ```/day3Teacher```: Day 3 x. Teacher of the Course
 - ```/day4Teacher```: Day 4 x. Teacher of the Course
 - ```/day5Teacher```: Day 5 x. Teacher of the Course



# Developer
 - [fireganqQ](https://github.com/fireganqQ) Thank you for the improvements.
 - **Teknofest2022**
