# faceteam
an application for getting to know people in a school/ professional setting

Raw text from the letter:
The projects I have in mind include:

- Going thru this course https://urldefense.proofpoint.com/v2/url?u=https-3A__www.wa4e.com_&d=DwIFAw&c=eyK8KBY19DualCOSet0JGw&r=-qYY0Igq-_79f8DH4ZPeM6WTOisUDhWgZ60Fr9OBrSY&m=_XVJWKrj25xxGMjTglDtLGiyFE_Vc2xIcuVFdUZjBqc&s=w0Z2yUgl5Mk199D4YEGNxftMR2ms4zCNlOPzOyBdfKc&e= , and making notes/improvements/updates etc... for a companion guide (you were good at this with my stuff). I've just created a document for this for you and me: https://urldefense.proofpoint.com/v2/url?u=https-3A__docs.google.com_document_d_19q-5Fi6kI-5F-5F1HXgw5n8UJfmklM0KMfRKLx50JwOjWBgd0_edit-3Fusp-3Dsharing&d=DwIFAw&c=eyK8KBY19DualCOSet0JGw&r=-qYY0Igq-_79f8DH4ZPeM6WTOisUDhWgZ60Fr9OBrSY&m=_XVJWKrj25xxGMjTglDtLGiyFE_Vc2xIcuVFdUZjBqc&s=Up-t-8rX58vZ2Z8a1QtI018MaqzDizPNT-_SJLbe7qI&e=

- The same for https://urldefense.proofpoint.com/v2/url?u=https-3A__www.py4e.com_&d=DwIFAw&c=eyK8KBY19DualCOSet0JGw&r=-qYY0Igq-_79f8DH4ZPeM6WTOisUDhWgZ60Fr9OBrSY&m=_XVJWKrj25xxGMjTglDtLGiyFE_Vc2xIcuVFdUZjBqc&s=Oz0g1b02xMzPhlkRE8V4WWW-qQ5f0H0I5SP9ypQMUrI&e=  https://urldefense.proofpoint.com/v2/url?u=http-3A__www.dj4e.com&d=DwIFAw&c=eyK8KBY19DualCOSet0JGw&r=-qYY0Igq-_79f8DH4ZPeM6WTOisUDhWgZ60Fr9OBrSY&m=_XVJWKrj25xxGMjTglDtLGiyFE_Vc2xIcuVFdUZjBqc&s=3TKr7TrvyZZrRjXmrxl1MEXXun2SpYQun2UIXH3vYxo&e=


- creating a standalone web app that does the introductions using php/mysql - which can run on your students site. (students.cpcc.edu has information about the database and you would set it up initially on xampp on your machine).  We would want a data model for the information that includes a user table, and probably a table for attributes and another for values (so Tasia is the user, an attribute is "Professional Background" and a value is "Worked as an engineer for ....."  so my first mental revision is 3 tables, but i haven't thought much more about it. Eventually we would want security, and roles, so that an admin could add and remove and edit everything, whereas the user could only edit their own entry. Probably would also want a log table for tracking changes and logins. Then viewers would have different rights, and could search, view one or many... a rough protoype is here: https://urldefense.proofpoint.com/v2/url?u=http-3A__wesome.us_CP-5FWEB250-5FSP2020_&d=DwIFAw&c=eyK8KBY19DualCOSet0JGw&r=-qYY0Igq-_79f8DH4ZPeM6WTOisUDhWgZ60Fr9OBrSY&m=_XVJWKrj25xxGMjTglDtLGiyFE_Vc2xIcuVFdUZjBqc&s=rFnZEfjsq319rgA2lTOQ737wAoiG--aummXB-F5gh5c&e=  - I have just created a repo for this called faceteam, and added you (and two others) as collaborators: https://urldefense.proofpoint.com/v2/url?u=https-3A__github.com_divonbriesen_faceteam&d=DwIFAw&c=eyK8KBY19DualCOSet0JGw&r=-qYY0Igq-_79f8DH4ZPeM6WTOisUDhWgZ60Fr9OBrSY&m=_XVJWKrj25xxGMjTglDtLGiyFE_Vc2xIcuVFdUZjBqc&s=tVKGRJUbXH4svg1TEzlVexImZrifh6LC-oqnzP6pJWA&e=


- creating a tool to help advise students on which classes to take, and when: specifically i usually have them go to mycollege, progress, list all the courses they need, and then move them into a 2-year format like:
SUMMER 2020


FALL 2020

SPRING 2021


and so on

and then put some courses (like WEB250 and WEB215) where they HAVE to go (spring of last semester usually) or CAN go (i.e. WEB210 is only in the fall) and shows dependencies (i.e. WEB110->WEB115->WEB215)

This could get very tricky with the modeling but would be interesting too.


- I believe the best way to learn programming basics is to do things again and again and again. So i want to have a website where you can pick a language and a type of basic programming (i.e. a few lines of code, or a loop) and the page will randomly generate a problem. The user wll ahve to code the solution, and then the page checks their code. A student protoyped this, but never got much past that. I'd start with JavaScript and a loop. Happy to expand on this if it interests you.


- LearnSwim:
Over the years of teaching i've decided that for all learning there are different levels based on experience and curiosity and need- as a teacher, if i write too many details, students don't read what i wrote. If i don't write enough, they don't get all the information they need. I'd like to have a platform where I can have multiple nested items for lessons. So for example:

Make an Introduction Webpage (is level 1)


Create a webpage called introduction.html with your name, photo, caption and bullets for professional, personal, and educational backgrounds, a sublist of courses you're taking, and a funny story to remember you by, as well as anything else you'd like to share.

Add a list of links to github, your student webspace etc....  (is level 2)


Using a text editor, create a page and put blah blah blah... (level 3)


HTML pages are just text, and you can edit it with any text editor, including notepad and notepad++ and even VS COde... you should not use tools like Microsoft Word (level 4)


Make sure your computer is on. See if it has notepad++ installed. Find the application and double-click it to open it up.... (level 5)


The idea is that the user can go as deep as they need/want to get the job done, and expand and collapse it as they go. So if they fully understand it, they can collapse all the text and just read the top level item. If they're new, or confused, they can keep expanding down to the tiny details that someone else might not need or care about.

I have some ideas for the interface that could involve checkboxes/clicking and some "expand all" "contract all" options.



So that's some to pick from. A related option would be to create a company to act as an umbrella for these projects, and make it easier/better for students to get internships/coops more "officially"
