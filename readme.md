# Views in Express

## Introduction

We've set you up in starter-code with an API for capturing your favorite embarrassing quotes – Quotes, Inc. We've thrown in a few styles for you, too, but you might have to mimic some class names and templates. Feel free to delete our style and fancy it up on your own.

Your goal will be to convert an Express JSON API to render full HTML views. It's up to you to take it from JSON to EJS, and we haven't given you a lot to start with. This will be good practice for installing the tools you need and setting them up from scratch.

If you are unsure of where to start, the [previous lesson](https://github.com/den-wdi-2/express-views-lesson) will be a helpful reference.

## Exercise

#### Requirements

- Use EJS to create views for your RESTful routing as follows:
  - Add `ejs` configuration to `app.js`
  - Create a `views` directory
  - Create an `index` page\*
  - Create a page to create `new` quotes with a form\*
  - Display these pages with your controller
  - Create one partial for a footer that gets rendered on each page
  - Create one partial for a header that gets rendered on each page

\* It may be a good idea to use Postman to POST some sample quotes to test these pages

- Render forms that submit data back to our Express app to make a full-stack app

#### Deliverable

Do as much as you can – the more complete the better – but at the least you should strive to create an index & a new page to POST to your create action.

Do your best to make it stylish, bonus points for prettiness.  Below is an example of an `index` page and a `new` page.

<img width="752" src="https://cloud.githubusercontent.com/assets/25366/9153289/98b3a226-3e02-11e5-95dc-2f44b5393f5c.png">

<img width="752" src="https://cloud.githubusercontent.com/assets/25366/9153304/4ea3903c-3e03-11e5-9af5-82b63257475f.png">

## Additional Resources

- [http://www.embeddedjs.com/](http://www.embeddedjs.com/)
- [Use EJS to Template Your Node Application](https://scotch.io/tutorials/use-ejs-to-template-your-node-application)


## Licensing
All content is licensed under a CC­BY­NC­SA 4.0 license.
All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
