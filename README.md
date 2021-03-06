# Survey form with React - the Sweet-o-meter 🍭 🍬 🍭 🍬 🍭

View the Sweet-o-meter here:

https://jovial-mcnulty-256bca.netlify.app/

The project this week was to use React to build a survey form. The completed project should consist of at least 3 questions that need to be answered by users. When the user presses submit, they should see a summary of their answers.

The app should also take accessability into account.

## The project

This week I have practiced using form fields with React and how to use the useState hook to store states in i.e. a file such as App.js

My goals was to have an app that only shows one question at the time and that on onclick changes the states of the question component. I'm not quite there yet. What I did manage however is to have a form with four questions using four different kinds of input: text, radiobuttons, select and checkboxes.

And when the user clicks the button after answering all four questions the questions are replaced by a summary. In that view I also have a refresh button that takes the user back to the first view.

I have also practiced components and further my understanding of how to share values between components using props and destructuring.

I put the form element in App.js and created components for each question, the header and the button. These were all created in their own files, And I created a css-file for each js.component. This structure seemed to make logical sense in my mind.

For validation I used 'required' on all input areas.

The app is responsive.

## Accessability

The requirements also stated that the app should take accessability into account (as it always should I guess)

It has keyboard navigation through tab and enter. This I achieved using tabindex, label htmlFor and aria-label. The radiobuttons turned out to be the hardest to target with a screenreader.

Tools I have used for testing accessability:

- Screenreader: Chrome Vox and the in-built Apple tool
- Wave audit
- Iphone speak screen
- Chrome dev mode to check structure without CSS
- Chrome dev tool Lighthouse - the app scored 96% on accessability (not great on performance though..)

The app was tested on Iphone X, desktop, and in Chrome, Firefox and Safari.











