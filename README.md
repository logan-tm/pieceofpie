# Piece of Pie Documentation Model

This is an experimental documentation classification model for long-term documentation. It is meant to be used by developers and businesses, but can also be used personally for organizational purposes.

---

## Breakdown
*'Piece of Pie'* is an anagram, and each of the letters represents a documentation classification.

### P: Project
A **project** is defined as an ongoing effort to reach a defined goal or conclusion. It is also defined as a "realized idea".

Examples:
- Making a coffee mug from scratch
- Updating software project from Node v16 to v18

*For those versed in Agile methodology, you'll typically work on story cards or bug cards as projects.*

### I: Idea
An **idea** is defined as a thought or note that may be actionable. It is also defined as an "unrealized project".

Examples:
- Make my own custom dishware
- Take over the world
- Make the website more "user friendly"

*This distinction between ideas and projects exists solely due to the fact that ideas are not always actionable or actualized, at least at the present moment. For instance, "take over the world" is a swell idea, but unless you're a small white rat with an oversized brain, chances are slim you'll actually try. Similarly, "make the website more user friendly" may be out of scope for your team right now and may be placed on the back burner until it can get the attention it deserves.*

*Noting an idea is great for documentation sake as it may better describe the direction you or your team wants to go in the future for projects.*

*For those versed in Agile methodology, you'll typically convert ideas into projects during refinement and sprint planning meetings.*

### E: Entity
An **entity** is defined as a person, group of persons, living thing(s), etc. In simpler terms, an individual or group that can be personalized with a name or id can be considered an entity.

Examples:
- Me, Logan Michalicek
- My cat Alice
- My business, Full Spark Development LLC
- My DnD group, the Knights of Silliness

*You may be so inclined to include inanimate objects in this description. Personally, I don't consider my coding companion duck "Roger" an entity, nor my SUV identified by vin, but I leave the details up to you.*

### C: Concept
A **concept** is an abstract representation of a shared definition. It can also be defined as a 'non-existent object'.

TODO: I would like a better description for this. If anyone has any ideas, please let me know!

Examples:
- The concept of natural numbers
- Agile methodology
- Functional programming vs OOP

### E: Environment
An **environment** is a descriptor for use of a place, object(s), etc. This class is more "loosey-goosey" than most others, and can be left open to interpretation.

Examples:
- A birthday party for an 11 year old vs a birthday party for a 21 year old
  - Same type of event, ***much different environment***
- An office space closet used for IT storage vs an office supplies closet
  - Same closet, different use case
- A production environment of EC2 instances vs a testing environment on an identical deployment of EC2 instances

*For a bit of a personal example, I like to split my day-to-day activities into buckets such as "Work", "Personal", "Professional", etc. I classify these buckets as Environments, and they contain information regarding what apps are available, what accounts I use, etc. This way, I can browse reddit for cat memes in one environment, then once I switch to my Professional environment reddit is full of Python and Web Development resources.*

*This was the original inspiration for pieceofpie.*

### O: Object
An **object** is a thing. Really. If it can be described as a thing to be interacted with, it can most likely be described as an object.

Examples:
- A coffee mug I made from scratch
- An EC2 instance or S3 bucket
- The sun (*if you don't consider it an entity*)
- A document, file, or a link to a file
- A YouTube video

*This is probably the most open-ended class in this list. It will be extended later.*

### F: Formula
A **formula** is a step-by-step process for completing a task.

Example:
- A chili recipe
- How to deploy a server to a VPS

### P: Place
A **place** is a physical or non-physical location, such as an office building or a website.

Examples:
- My house
- The bus stop
- github.com

*Whether a website is considered a 'place' is currently in debate, but at the moment it is.*
### I: ???
Unknown at the moment

### E: Event
An **event** is a representation of a time-stamped happening. For most things with a time element, an event will most likely be used.

Examples:
- My daughter's birthday party
- An error with a log from a server

---

## Use Cases

The best thing about this model is: it can be used anywhere. It's meant to be flexible and non-opinionated. It fits as an underlying structure to *your* documentation strategy, and you take care of the rest as you see fit!

Here are some examples.

### Personal Organization
In this instance, I consider each classification a box on a checklist. That is: I should have a method for organizing all of my events, entities, ideas, etc.

Therefore, I will use this model to map to the solutions I use to manage that section.

Projects: Trello
Ideas: Notes App
Entities: Contacts/Email App
Concepts: Notes App
Environments: Notes App
Objects: Storage garage
Formulas: Notes App / Recipe book
Places: Maps App
I???: ???
Events: Calendar App

### Business Organization
It may be helpful for an IT department to map out a similar list as above for the employees of their company.

Projects: JIRA
Ideas: Confluence
Entities: Microsoft Outlook + Active Directory
Concepts: Confluence
Environments: Confluence
Objects: Amazon S3, local hard drive storage, on-site storage
Formulas: Confluence, physical documentation
Places: Facilities Dept, Google Maps
I???: ???
Events: Microsoft Outlook, Microsoft Teams

---

Note: I still need a word starting with either 'F' or 'I', as 'Formula' can be substituted with 'Instruction'