# TheraPsy Flutter Interview Technical Test
Welcome to the technical interview for the Flutter developer position at TheraPsy.
This interview is divided into two parts:
- I. Scenario Questions: This is a simple test to see how you would solve certain programming scenarios. This part should take around 15 minutes.
- II. Practical Coding Challenge: This is a practical test to check your ability to work with Flutter. This part should take around 45 minutes.

# I. Scenario Questions
You can find the form about the scenarios here:
https://forms.gle/3w7TiWmQ25uvbML2A

# II. Practical Coding Challenge
This is a quick flutter test to see what you are capable to achieve in a real world scenario.
You should be able to finish this part in about 45 minutes.
You will be mainly scored by **your process**, the **quality of the result** and also the **amount of time** you took.
It can help to first check out the code, as some parts to help you complete tasks have already been added, which might get overlooked otherwise.

## Rules

1. You can use Google etc for research, however ChatGPT/Copilot and other AI models are not allowed.
2. If you don't understand an instructions please feel free to ask the interviewer.
3. The interviewer should not give you hints unless strictly necessary.
4. Let the interviewer know if you have finished the test earlier.

### Instructions
> **NOTE**: The instructions do not have to be done on this order, feel free to jump between tasks.

### How is the final look of the app
![screenshot](/screenshot.jpeg)

#### TASK 1 - Minor UI changes
- Change the app bar name to `TheraPsy Interview Test`
- Make some small UI adjustments to give the app a bit of a better look and feel, but dont spend too much time on this

#### TASK 2 - List all users
- List all the users on the home screen (Mock data should be in `data/mock_data.dart`)
- We want to see the first name and last name as a title
- We want to see the role as description

### TASK 3 - User Avatar
- Show the user image on the left
- The user image should have a placeholder (in case there is no image), please add the package https://pub.dev/packages?q=font_awesome_flutter and use `FontAwesomeIcons.image`
- We want the user avatar logic to be a widget, please refactor it in a new file `widgets/avatar`

#### TASK 3 - Bug Fixing
- `Add user` button is not working, we want a new user to be added but when we press the + button it doesn't do anything
- Clean up the search controller when the widget is removed from the widget tree.

### TASK 4 - Features
- Add a search to filter that filters by user's first name, last name, role and email

### TASK 5 - Suggestions
- What would you suggest to improve the code
- How would you proceed to implement a new user form to replace the simple "add_user" button?
