## Project 2: Build a sound machine

Fulfill the below user stories and _**give this app your own personal style and add new functionalities**_! 

![Picture of the sounds machine](https://i.imgur.com/hrWJ6Uw.jpg)

You should build this frontend project using **React.js**. You are allowed to use a CSS preprocessor like SASS or LESS, and a state mangement tool like Redux, but this is not mandatory.

However, the better you make it, the more you’ll learn, the more you'll impress and get you closer to the job. 

---

### User Stories

**User Story #1**: I should be able to see an outer container with a corresponding `id="sound-machine"` that contains all other elements.

**User Story #2**: Within `#sound-machine` I can see an element with a corresponding `id="display"`.

**User Story #3**: Within `#sound-machine` I can see 9 clickable pad elements, each with a class name of `sound-pad`, a unique id that describes the audio clip the sound pad will be set up to trigger, and an inner text that corresponds to one of the following keys on the keyboard: Q, W, E, A, S, D, Z, X, C. The sound pads MUST be in this order. Feel free to use any sounds you like!

**User Story #4**: Within each `.sound-pad`, there should be an HTML5 audio element which has a `src` attribute pointing to an audio clip, a class name of `clip`, and an id corresponding to the inner text of its parent `.sound-pad` (e.g. `id="Q"`, `id="W"`, `id="E"` etc.).

**User Story #5**: When I click on a `.sound-pad` element, the audio clip contained in its child audio element should be triggered.

**User Story #6**: When I press the trigger key associated with each .sound-pad, the audio clip contained in its child audio element should be triggered (e.g. pressing the Q key should trigger the sound pad which contains the string "Q", pressing the W key should trigger the sound pad which contains the string "W", etc.).

**User Story #7**: When a `.sound-pad` is triggered, a string describing the associated audio clip is displayed as the inner text of the `#display` element (each string must be unique).


***

Once you're done, upload your project to your github and submit a URL of your working project to your class. You can use https://www.netlify.com/ to do so. You will be asked to explain your code and learnings on our upcoming session so that you can improve both yous skills and the project itself.

After feedback and revisions do not forget to add the project to your CV to spark the interest of recruiters and hiring managers and to show you are passionate about programming. For more information on how to add personal projects to your CV check [this article](https://www.freecodecamp.org/news/writing-a-killer-software-engineering-resume-b11c91ef699d/).

Happy coding!
