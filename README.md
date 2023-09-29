
#  Retro Shoe Landing Page - Assignment 1(Tailwind)

## Hosted Link
You can view the project live at [View Live Project](https://saifulislam05.github.io/shoe-card-tailwind-ass/)

## Code Explanation

### HTML Structure

#### `<body class="w-screen h-screen flex items-center justify-center font-IBMPlex">`
- Sets the body element with a full width and height, centering its content both vertically and horizontally.
- Uses the "font-IBMPlex" class for the font style.

#### `<div class="card w-[68rem] h-[32rem] flex flex-col px-12 pt-10 pb-14 shadow-xl bg-gradient-to-t from-black to-black to-35% from-white from-65%">`
- Creates a card element with specific width, height, padding, and shadow.
- Applies a gradient background from black to partially transparent black and then from white to partially transparent white.

#### Inside the Card:

##### `<div class="wrapper flex max-h-fit">`
- Wraps the content inside a flex container with a maximum height set to fit its content.

##### Inside the Wrapper:

###### Left Column:

- `<div class="image-box w-2/6">`
  - Contains an image with a specific width of 2/6th of the parent container.

- Right Column (`<div class="grow content-wrapper flex flex-col ml-14">`):

  ###### Upper Section:

  - `<div class="upper font-medium text-white">`
    - Contains the product title and price.
    - Font weight set to medium.
    - Text color set to white.

  ###### Sizes Section:

  - `<div class="sizes flex mt-28 gap-8">`
    - Contains size options (XS, S, M, L, XL) displayed as buttons.
    - Buttons change color and add shadow on hover.

  ###### Buttons Section:

  - `<div class="buttons mt-12 flex gap-8">`
    - Contains "BUY NOW" and "ADD TO BAG" buttons.
    - Buttons change background, text, and border color on hover.
    - Also contains a heart icon that changes color on hover.

  ###### Additional Information:

  - `<p class="mt-6">Free Shipping on all continental US orders.</p>`
    - Displays a message about free shipping.

### CSS Classes Explanation:

- `w-[68rem]`, `h-[32rem]`: Sets specific width and height for the card.
- `shadow-xl`: Applies a large shadow to create a sense of elevation.
- `bg-gradient-to-t`: Specifies a top-to-bottom gradient background.
- `from-black`, `to-black`, `from-white`, `to-white`: Defines colors for the gradient.
- `max-h-fit`: Sets the maximum height to fit the content.
- `shadow-green`, `shadow-green-small`: Adds green shadows to elements for styling.
- Various text size classes (`text-5xl`, `text-3xl`, etc.) are used for different text elements.
- `bg-[#2dd4bf]`, `hover:bg-black`, `hover:text-white`: Sets background and text colors for buttons and changes them on hover.
- `text-[#1bc8bb]`: Sets a specific text color.
- `cursor-pointer`: Changes the cursor to a pointer on hover, indicating interactivity.
