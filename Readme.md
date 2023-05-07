# Experience Day. Senior Frontend Engineer.

## Basic conditions

You received this tech case a few days before the actual "tech interview". Please take your time to read over everything and try to understand it.
In general: there is not much to code here, but to show your experience in dissecting a feature request and think about possible solutions. Get ready, and have fun.

### Timing

- We expect, that both tasks will take a maximum of 90 minutes for you to solve -
  - task 1: approx. 60 minutes
  - task 2: approx. 30 minutes
- try to stick to these time constrains; do not "over think" the tasks
- clarify questions and uncertainties beforehand

## Task 1: feature request for a filter to a product catalog

### The Story

We have a customer with a website to sell marble tiles (think of "Prada 👜" for tiles).
Right now, all his products are listed on one page on nice "cards" with image and title.
He has increased his range of products, and now he needs to adjust the website to accommodate the new situation.

### The challenge:

The customer wants us to consult him to implement a "filter feature" for his product list. He is not very specific and has no idea what to expect and what to ask for. Since he was not able to deliver a list with acceptance criteria, we will have a workshop with him.
You are the senior developer on the project, and will lead the workshop.

### The role play:

In the interview we will have a role play, where we are the customer and you have to make sure, that you get all information out of us, to provide the best solution for his/our feature request.
See To Do section for your tasks…

### Customer requirements

- Filters for:

  - color (10x e.g. red, gray, …)
  - design collection (4x e.g. outdoor, kitchen …)
  - availability (true|false)
  - surfaces (4x e.g. matt, shiny,…)
  - material (6x e.g. marble, stone, …)
  - sizes (16x e.g. 4x4cm, 6x6cm 8x8cm,…)
  - search field with full text search in titel and description of the data
    - nice to have: type-a-head feature

- Reuse the customers existing REST API (it will be able to provide all data we need)
- Responsive Design

### Your To Dos

- dive into the feature request and come up with questions for the customer to answer
- create a list of questions (simple bullet points are fine; maybe have a simple and a advanced variation for him to choose from)
- if you need: create a very simple presentation to help the customer understand your questions (e.g. screenshot of simple mock image of the position of the filters (top vs. left))
- last, but not least: try to estimate the effort for your team to accomplish a simple version (minimum requirements) and very polished version (max. features)
  - assume the following: we have a design system in place (CSS for inputs and selects) and the API is ready to use.

## Task 2: Code review

You are working on the mentioned project and have a small team of co-workers.
One of the junior devs handover to you [storage.js](./src/storage.js). On the first look it seems ok, but then you try to make it run...

### To Dos

- Try to understand what [storage.js](./src/storage.js) should do
- Let's have a role play:
  - in the onsite interview we will have a "code review" session
    - we are the junior dev and you do a code review with us
- part of the role play should be the introduction to unit tests
  - make sure, that the tests are running and provide a minimum of 2 tests
  - we can discuss, if there are more cases, we should cover
