# Lab 4

This project consists of a given website created using basic HTML/CSS where we are instructed to improve the accessibility of the website for users who may not be able to percieve information as most people are.

## Accessibility Lab Answers

- Color: Changing the text color to white makes the text much easier to read compared to the black

- Semantic HTML: I updated the HTML to put all the titles in respective h1,h2, and h3 tags, and to put all the text in p tags which they weren't in. I also updated the names of therespective css classes to match the new tags. I also used the nav tag for the navigation div and updated the css for it as well.

- The Images: Added alt text for each image describing what it is for screen reader users

- The Audio Player: Added a <details> tag underneath the audio player for imparied people to be able to read the transcript. Moreover, there is also an option for users to download the audio files in case that older browser the user is using doesn't support the audio tag

- The Forms: Added a label to the search query allowing only screen readers and added a css class for it. Modified the comment form text labels to be in label tags and added them to the correct css rules to make them visible and in the same style as the rest of the site.

- The Show/Hide Comment Control: Added the tabindex attribute to it and set it to 0 to make the button accessible by using the tab key and being also able to be activated using the return key.

- The Table: Added a caption tag to the top of the table to desribe what information is being displayed on the table. Moreover, I also added the scope attribute to each column to allow user to distinguish between the columns.

- Suggestions:

1. I would suggest to continue and improve the color contrast of the website. Even with the updated text color, the green background in my oppinion makes it tough to read for visually impaired users. I would suggest using high constrast colors and larger font sizes.

2. I also would suggest creating some contrast for the comments as well as the comments are hard to read. A defined box for each comment to be in would be nice.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```

This will install the necessary dependencies for the project.

### Running the Site

1. Open `index.html` in Visual Studio Code.
2. Install the Live Preview extension.
3. Start the Live Preview server by clicking on "Live Preview: Start Server".
4. Open the built-in debugger in VSCode.
5. Click on the debug icon in VSCode and then click the big green arrow that says "Debug Website" to start a debugging session.

## Testing

No Tests Available for this lab

## Sources Used:

None used.
