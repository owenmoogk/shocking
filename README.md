# shocking
it's shockingly moral (Jamhacks 6)

we didn't win because of 'political reasons'... apparently its not moral to taze people :(

https://www.youtube.com/watch?v=93MGAAmkYUM

# About the Project
## Inspiration
Going into university next year, protecting belongings in open places is very important. Especially after Janik decided on going to Western University, and we both are planning on travelling over the summer, protecting belongings in a new environment should be a priority. After I, Owen, was stolen from right out of my backpack, we decided to take action.

## What it does
Assembled in a backpack, the shockingly moral solution uses a small electrical setup to prevent theft. Utilizing a step-up transformer, we built a miniature (harmless) taser, that will stop thieves in their tracks.

## How we built it
This was built with simplicity in mind, with a small number of components working seamlessly together. It was designed to work effectively, and be lightweight and not take up a lot of space, as it would have to be carried around by the user anytime they wanted to use a backpack. Using an Android app built with MIT App Inventor, Bluetooth signals can be sent to a password protected Bluetooth module connected to an Arduino Uno. The app will signal to the electronic system when to enable the circuit, and can arm or disarm the security system. When the system is armed, a current is passed through a relay which activates a separate circuit. This second circuit contains a 3.7 V LiPO battery, which powers a step-up transformer, converting the charge to 4000 V. The leads from this circuit are attached to the zippers of the backpack, and the circuit is completed when the thief touches both zippers. There are measures in place to ensure that the zippers do not come into contact with each other, shorting the circuit.

## Challenges we ran into
There were a few challenges that we ran into while building this project. One of these was being able to communicate from the Android app to the Arduino. This was problematic due to developing the app on a computer, however it had to be tested on mobile. This made the iteration process cumbersome, however once this was fixed it was fairly smooth sailing on the app front. Another issue that we had was separating the zippers on the backpack. If we did not do this, it would short circuit and could turn from a harmless taser to a dangerous potential hazard. We had to go over multiple iterations to make sure that it was safe and somewhat discrete.

## Accomplishments that we're proud of
We are very proud of the end result, as we believe that we integrated the solution well and were successful in solving the problem at hand. We are also proud of the integration with the Android app, as it is very seamless, and we can see it being a simple and easy way to control the backpack (it is not an annoying process to use on a day to basis). We are proud that we were able to make people *ecstatic* about the project and the engineering.

## What we learned
We had to do a lot of research about how a relay works. Using this program, with multiple different levels of voltage and current, we needed to have two separate circuits that could communicate with each other. This was accomplished with a relay, but we didn't know how to use this at the start. After a lot of research, we feel like we understand the topic much better, and will be able to apply it in the future. We also learned about the integration of Android apps. Having not used these android apps to communicate with an Arduino, it was interesting to see the process to connect the two seemingly opposite components, which ended up working well together.

## What's next for Shockingly Moral
We want to continue working on this project, and the first obvious thing to do is to make the system integrate into the backpack zippers with more fluidity. There is currently tinfoil wrapped around the zippers, which makes it pretty obvious (and not very fashionable). We can fix this by having a bit more time, and being able to drill holes in the zippers, as well as being able to add insulation to the bottoms. This will make the backpack have the original look, and will be a much cleaner way of accomplishing the same product.

also:

the app is drippy 😫🥶🥶😫🧊🧊😫😩😩🥶🧊
