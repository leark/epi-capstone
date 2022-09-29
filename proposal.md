# Project Proposal

## Name of Student: Seung Lee

---

## Name of Project: Coffeetron (combination of coffee + electron but might change)

---

### Project's Purpose or Goal: (What will it do for users?)

Purpose of the project is to create an app that's available on Windows that keeps track of coffee making workflow. User can input what type of brew method, weight, temperature, tasting notes and other information that can be viewed later. Electron is a Chromium based framework that can be used to build a desktop based application for Windows, Mac, and Linux. Thus as a stretch goal, the project can be scaled to be available on different platforms as well.

---

### List the absolute minimum features the project requires to meet this purpose or goal

  1. User can choose a brewing method template
  2. User can input amount of coffee
    (all measurements can be in metric or imperial unit)
  3. User can input amount of water
  4. User can input tasting notes
  5. User can choose a popular template + input amount of coffee and program will automatcially calculate amount of water and other stuff needed to brew a specific ratio.
  6. Keep track of all the drinks user made
  7. User can log in

---

### What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific

* Electron as base framework
* JavaScript for scripting
* React for component rendering
* CSS for styling
* Firebase for account management
* Local database (initially JSON file and option to use Firebase as stretch goal)
* (Undecided on UI Library -> Bootstrap vs. Tailwind)

---

### If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific

  1. User's data is synced when logged in
  2. Show visualization for the drinks user made
  3. Have visual option to show/add to the workflow
    (such as creating boxes with input fields and connecting them)
  4. Show timer and alerts user to do certain step when appropriate
  5. Have the app work on different platforms
  6. Let users order coffee beans
  7. Make it work on Linux (not sure on which)
  8. Make it work on a browser
  9. Make it work on a Mac

---

### What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?

* Firebase for database
* D3 for graphs and visualization
* Not sure what's needed for ordering more beans. Perhaps shopify?

---

### Is there anything else you'd like your instructor to know?

  The plan might change to just web app if Electron proves too hard to use
