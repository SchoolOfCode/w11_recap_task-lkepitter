# Dungeons and Dragons Character Creator

This app is my own take on a character creator for the Dungeons and Dragons (Fifth Edition) game, in the vein of the official [DNDBeyond](https://www.dndbeyond.com/).

The current version simply displays pre-built characters from given data. In future versions I'll add the core functionality: letting the user actually edit the fields to create their own!

I haven't yet finished the entire display and the maths under the hood. Ideally I'll have one or more components do the calculations for the character stats and the Display will simply show them, but at the moment it's doing the calculations.

## Other planned features:

- Save to and load from local storage (possibly also save/load to online DB storage - hence express and pg dependencies)
- Hamburger menu for character save/load and additional options
- Level up options in the left side menu to allow easy character changes and pre-build (a great feature in a similar app for the Pathfinder game)
- Data fetching from the [D&D 5e API](https://www.dnd5eapi.co/) for easy rules integration
- Plugin custom data for homebrew and third party game content

---

# Week 11 Recap Task

## Feedback

### Peer feedback

Feedback is a vital part of continual improvement and the hero's journey of growth you're on on this course. We're here to support each other to grow on this bootcamp journey, so keep this in mind when you write honest, constructive feedback. This is important for the receiver of the feedback as well as the giver - learning to give feedback is a skill that you'll use throughout your career in tech.

Please click [here](https://forms.gle/BJWLNvSgKsp9rkbF8) to fill out the peer review form for your partner this week. Please fill it out for each person you've worked with.

### Coaching feedback

If you didn't complete the coaching feedback survey about your recent 1:1s with your coach earlier in the week, please [click here](https://forms.gle/rwcyW9bTbVqX4nNz6) to do so.

## Task

This week we have covered a lot of ground

- Docker
- Custom Hooks
- Scope
- Recursion
- Couchbase
- JS Quirks
- Architecture
- Debugging

PHEW! that was a lot of subjects. For this week, your task involves planning out an application, using the disney ideation we taught you earlier on in the course. Using the below suggested problem statement, or an idea of your own, use all you have learned to date, think about how you might plan out this full application, putting that in this repository - we would suggest [draw.io](draw.io)

You may also want to consider how you would overcome some of the quirks shown this week - would testing help here maybe?

## Suggested Problem Statement

You have been contacted by a company who wishes to help its employees to understand how their time is being used up more effectively. Budget is not a problem. You are to design a service that will record effectively how time is being used, from breaks, to meetings, to toilet stops, to commutes and more. consider what you might wish to do to collect that data.

This recap task is quite open so focus on practising your planning skills first. Be as imaginative as you want (think calendar integrations, automated time logging etc) and draw your system architecture out. Don't worry about implementing it, when you get to coding focus on the areas you want to improve on; that could be making a React app that you want to integrate with Couchbase, or using a UI library that provides charting components to create a visual dashboard that displays time spent on a graph (and other key metrics).
