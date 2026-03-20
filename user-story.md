---

name: User Story
about: This template defines a user story.
title: ''
labels: ''
assignees: ''
-------------

## User Story Template

**As a** [role]
**I need** [function]
**So that** [benefit]

### Details and Assumptions

* [Document what you know]

### Acceptance Criteria

```gherkin
Given [some context]
When [certain action is taken]
Then [the outcome is observed]
```

---

# 1. Finish user stories

**As a** Full-stack developer
**I need** to complete all user stories for the GiftLink project
**So that** the team has a clear understanding of requirements

### Details and Assumptions

* Covers both frontend and backend tasks
* Based on agreed project requirements

### Acceptance Criteria

```gherkin
Given the project requirements are defined
When I create user stories
Then each story must include role, function, and benefit

Given the user stories are written
When I review them
Then each story must include details, assumptions, and acceptance criteria
```

---

# 2. Initialize and populate MongoDB

**As a** Full-stack developer
**I need** to initialize and populate MongoDB
**So that** the app has structured data

### Details and Assumptions

* MongoDB is used
* Initial dataset is available

### Acceptance Criteria

```gherkin
Given MongoDB is installed
When I create database and collections
Then structure must match requirements

Given initial data is available
When I import data
Then all documents must be stored successfully
```

---

# 3. Run skeleton application

**As a** Full-stack developer
**I need** to run the skeleton app
**So that** I verify setup

### Details and Assumptions

* App dependencies are installed

### Acceptance Criteria

```gherkin
Given the application is set up
When I run the server
Then it should start without errors

Given the server is running
When I open the app in browser
Then the main page should load
```

---

# 4. Landing page and navigation

**As a** Full-stack developer
**I need** to build landing page and navigation
**So that** users can navigate easily

### Details and Assumptions

* Navigation should be user-friendly

### Acceptance Criteria

```gherkin
Given user visits the app
When homepage loads
Then landing page must be displayed

Given navigation menu
When user clicks links
Then correct pages must open
```

---

# 5. Authentication system

**As a** Full-stack developer
**I need** authentication features
**So that** users access securely

### Details and Assumptions

* Includes register & login

### Acceptance Criteria

```gherkin
Given a new user
When valid data is submitted
Then account must be created

Given a registered user
When valid credentials are entered
Then login must succeed
```

---

# 6. Gift details page

**As a** Full-stack developer
**I need** a gift details page
**So that** users see info

### Details and Assumptions

* Linked from list page

### Acceptance Criteria

```gherkin
Given gift list is displayed
When user selects an item
Then details page must open

Given details page loads
When data is fetched
Then all info must be shown
```

---

# 7. Se
