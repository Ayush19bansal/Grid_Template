# Hosted link https://ayush19bansal.github.io/Grid_Template/
# UI
![image](https://github.com/Ayush19bansal/Grid_Template/assets/118842033/b8cc7042-c548-42af-96cf-0b6b6b1fe241)

# HTML
![image](https://github.com/Ayush19bansal/Grid_Template/assets/118842033/36a86e6a-91b7-48b4-b8c6-a2a518ccf312)
![image](https://github.com/Ayush19bansal/Grid_Template/assets/118842033/6ee52892-2703-4121-b829-4bcfbf3b53f7)

This HTML code represents a webpage . Let's break it down:

1. The code starts with the `body` tag, which is the main content area of the webpage.

2. Inside the body, there is a `div` element with the class "container". This is used to wrap the content for styling and layout purposes.

3. Within the "container" div, there are five sections (`.item`) each representing a testimonial. Each testimonial section has:
   - An inner `div` with the class "title" that contains two child divs, one for the image and another for the person's name and verified status.
   - An `h1` element with a main testimonial headline.
   - An `h2` element with the actual testimonial text.

4. The testimonials include images, names, verified graduate statuses, headlines, and descriptive text.

5. The `img` elements inside the testimonials have their `src` attributes set to image file paths, and the `alt` attributes provide alternative text for accessibility.

# CSS
![image](https://github.com/Ayush19bansal/Grid_Template/assets/118842033/4bdeadc0-0450-4c8f-854f-48e19b5239de)
![image](https://github.com/Ayush19bansal/Grid_Template/assets/118842033/648e1fb2-24c9-4d67-a6c9-37dcdd1f8c84)
![image](https://github.com/Ayush19bansal/Grid_Template/assets/118842033/3c07a6fe-382d-4ab3-a114-6c5e87999a91)
![image](https://github.com/Ayush19bansal/Grid_Template/assets/118842033/5ddf0719-bec6-4120-82c1-b6c538f44331)

This CSS code provides responsive styling instructions for a testimonial section on a webpage. Here's a brief breakdown:

- The `*` selector applies styles to all elements, setting margins and paddings to 0 and using the border-box box-sizing model.

- The `:root` selector defines custom variables (`--color1` and `--color2`) to be used for consistent color management.

- The `body` styles set the background color, font family, minimum height, and centering for the entire content.

- Various `h1`, `h2`, `h3`, and `h4` elements are styled with different font sizes, line heights, colors, and margins.

- The `.container` class styles a grid layout for arranging the testimonial items. It specifies different areas for each item and adjusts padding, width, and margin properties.

- The `.item` class styles the individual testimonial item, including padding, border-radius, and a box-shadow effect.

- The `img`, `.title`, and different ID selectors (`#one`, `#two`, etc.) are used to style specific elements within each testimonial item.

- Media queries are used to create responsive layouts for various screen widths:
  - For screens up to 527px, the grid layout is adjusted to stack items vertically.
  - For screens between 528px and 607px, the grid layout is adjusted to fit items differently.
  - For screens between 608px and 863px, the grid layout is adjusted again.
  - For screens between 864px and 1199px, the grid layout is adjusted once more.

In summary, this CSS code provides a responsive layout for a testimonial section, with varying item arrangements and styles based on different screen widths.
