# React Dojos

## Dojo #1: Kaamelott's quotes table

You are asked to create (in React) an app listing the best Kaamelott quotes.

### Step 1: Displaying the quotes

Objective: split your React application into 4 components:

- `App` (black)
- `Header` (blue)
- `QuoteList` (red)
- `Quote` (green)

And integrate some basic data.

![Step 1](kaamelott-1.png)

### Step 2 : Detailed display of each quote

Objective : use props to pass all relevant data to your `Quote` component and have the detail about each quote :

- The quote itself
- The author
- The season
- The episode

![Step 2](kaamelott-2.png)

To do this, you can use the following api : [API citations Kaamelott](https://github.com/sin0light/api-kaamelott). It will give you directly usable data.

> ⚠ **Attention**, Don't try to use the API directly, only to test it in your browser to retrieve data. Retrieving data in a React application is a topic for another day ;-)

### Step 3: Storing likes

Goal: use `state` and `event handlers` to handle click events and update data.

![Step 3](kaamelott-3.gif)

To do this, you'll probably need to handle quotes with IDs. Look at [managing data modification inside tables](https://beta.reactjs.org/learn/updating-arrays-in-state) to do this properly.

### Step 4: Bonus - CSS

Goal: Make it look attractive, it's a rough-looking right now. You are allowed to add a little CSS.

## Dojo #2: The no-TODO list

To change a bit from the classic TODO list, we ask you to make a list of things not to do.

### Step 1: Display the no-TODO list

Objective: create a simple wireframe for a mini no-TODO list.

You will choose the way you want to display your no-TODO list.

> This step can be done all together, no need to start the timer in Dojo mode!

### Step 2 : Break down each item into components

Goal: split your React application into several components.

A possible breakdown could be :

- `App`
- `Header`
- `ItemForm`
- `ItemList`
- `Item`

### Step 3: Add items to the list

Objective: Add an item to the list via the new item form.

### Step 4: Manage the validation of a non completion

Objective: Mark an item in the list as not-done using a checkbox. You can change the style of the item (gray color, italic style and strikethrough).
