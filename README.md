# React_Redux_Blog

It's a simple blogging application. It's going to have the usual CRUD functions. 

In index page, it shows a list of all of our different blog posts that the user currently has. If users click on a blog post, users'll navigate to show page. Also, users can create new posts by clicking the ADD Post button on the index screen. 

In show page, it'll show just a single post in the middle.

In creating page, the user can enter a title, categories, and contents for the blog post. Once they click the Save button, it will save the record to a backend server and then it will navigate them back to the index page. Users can also click cancel button and go back to index page as well.

Using reduxblog.herokuapp.com as the backend server API.

Fetching a list of posts inside componentDidMount().

Implementing React Router to navigate Create Page, Post List Page and Post Detail Page.

Using Link tag to navigate different components.

Using redux-form library to handle any type of form with redux, to validate the input, and then to submit the form.

Using promise to ensure we navigate back to list of posts after creating a post successfully.

In index.js, we use react-router-dom, in particular the BrowserRouter, Route, and Switch components to give our application the aspect of the idea of navigation. We created separated routes for each invidual component and we tie each of those components to a particular path. Whenever a user navigates to one of these paths, it will show particular component. So we don't change HTML documents, we just hide and show different sets of React components.

We use ownProps system with mapStateToProps.

We use lodash mapKeys() to treat our state object as an object rather than an array. With an object, we can look up records easily and faster.

### Getting Started

There are two methods for getting started with this repo.

#### Familiar with Git?
Checkout this repo, install dependencies, then start the gulp process with the following:

```
> git clone https://github.com/kuanhanchen/Redux_Book_List.git
> cd Redux_Book_List
> npm install
> npm start
```

#### Not Familiar with Git?
Download the .zip file. Extract the contents of the zip file, then open your terminal, change to the project directory, and:

```
> npm install
> npm start
```
