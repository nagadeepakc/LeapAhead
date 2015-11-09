# Inspiration

The Education and Inequality tracks inspired us to create something fun/cool that was inclusive and educational for all types of children. Upon doing some research, we learned that those with intellectual disabilities learn best by breaking down tasks into small steps, performing hands-on tasks, by being in environments where visual aids are used, and by being provided direct and immediate feedback. These teaching methods gave us the idea for the super interactive game- "LeapAhead".

# What it does

Our app allows parents to sit down with their kids and help them with simple problems. The parent will read aloud the question and the child will point, using the Leap Motion sensor, to which ever answer he/she thinks is correct. If the child answers correctly, the parent will click the next button and go to the next question.

We take the hand coordinates provided by the Leap Motion tracker and constantly stream it to the frontend via a WebSocket in order to map 3D x,y,z coordinates to a 2D screen.

# How we built it

We used AngularJS to create a front end web app that connected to the Leap Motion sensor. We used  Leap Motion JS plugins in order to stream the live position data to the frontend. We then took that data and made events based off of where the user's hand most recent position.

# Future for LeapAhead

If a child is selecting the wrong answer continuously, we could give them a hint to the right answer. We could also provide characters that the children are more familiar with. For example if we asked a question about colors and one selection was the color yellow, we could use Spongebob as the answer choice instead of a plain yellow block. This allows children to map familiarity with new concepts. We could develop a reward/achievement system that would allow the children to see their progress. Adding profiles for children could create a more personalized experience for them as well- perhaps even adding a personalized greeting and encouraging phrases/quotes.

# Built with

*leap-motion
*node.js
*angular.js
*javascript
*firebase
*pure.css
*travis-ci
