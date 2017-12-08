# _Two Day SASS_

#### _By Lew Davidson_


## Description

A responsive site using SASS to achieve styling and the 7-1 file architecture to organize files.

### Wireframe - Plan

![wireframe 2 sketch](https://i.imgur.com/646LUdl.jpg)
![wireframe 2 tablet sketch](https://i.imgur.com/yPLc4kJ.jpg)
![wireframe 2 mobile sketch](https://i.imgur.com/YnJu6sO.jpg)


---
#### Thoughts and Feedback

This week I feel like I learned a lot about SASS and cemented my understanding of why it's used and how it's organized. Our learning process involved planing out a few potential layouts using wireframes, narrowing those down to our favorites, and then trying to conceptualize how to build it, starting from the mobile container - the mobile granular elements and moving from there out to tablet, and finally to desktop.

It was really helpful to have some set-aside time during the first day to be encouraged to just learn and dig around. I think that's what really furthered my learning about SASS. I picked up a few really great tips about grid and media queries.

What didn't really make sense was the table, it ended up feeling pretty forced.

What worked: going from mobile out, using a responsive grid, using flexible measurements for images and elements, having a referential wireframe.

What didn't work: Originally we used a complex set of media queries that ended up being too specific, the responsive grid ended up being too column-focused to work effectively for a desktop size.

---

#### Table

| Term | Description | Implementation |
| :-------------     | :------------- | :------------- |
| Variables | Variables are styles that have been defined in your variables file, that can be called upon in other files by name. This makes it easier and shorter to define styles multiple times by shortening things to a single word. | We used variables yesterday to define colors, screen size, and font-families. |
| Mixins | Mixins are a call-able group of styles that are defined once and called upon as many times as desired in other stylesheets. They are able to be passed variables and specifications as well, making them more dynamic than a variable. |  We used mixins yesterday to define media breakpoints, set up our math grid, and define styles for elements at different sizes. |
| 7-1 Architecture | A file structure that splits your s\SASS styles into seperate files and directories for each section of your site. The directories are then imported in to the main stylesheet, shortening it and increasing load-time as well as orginizing your file structure for large scale projects. | We used 7-1 yesterday to keep our styles seperated by section, or style type. This made it easier to find or change specific elements of our page as needed. |
| Nesting | Nesting is a SASS tool that allows you to "nest" child-styles inside their parent's styles for brevity, organization, and specificity. | We used nesting for almost the entire page yesterday. I found it really helpful to style the child elements or classes right along-side their parents. |
| Functions | A function allows you to to math with your styles, and also makes that math re-usable on your page. It's close to a mixin in functionality but different in that it can accept input and only outputs a single value. | We used functions yesterday, mainly only for colors. Specifically for similar colors or lightening or darkening our colors. |


---

### Changes to Approach

##### I will start off by building my mixins, variables, and media queries before styling or setting up size-specific rules. This will result in a smoother time when applying my styles later.

##### I will Be sure to make commits more often, as that was a struggle yesterday. I will be sure to use fluid styles and remember to think big, then small :).
---



## Technologies Used

* _CSS_
* _SASS_
* _7-1_

### License

Copyright &copy; 2017 **_Lew Davidson_** Student at Epicodus.
