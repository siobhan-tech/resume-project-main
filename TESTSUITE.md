### BDD Test Suite

### Rubric:

-   **Given:** Describes the initial context or precondition.
-   **When:** Describes the action or event that occurs.
-   **Then:** Describes the expected outcome or result.

As implemented, this suite should provide near-complete coverage for major portfolio features

#### A: Navigation

##### A.1: Navigation Links Functionality

**Given** I am on Siobhan Powell's portfolio website\
**When** I click on each navigation link\
**Then** I should be scrolled to the corresponding section on the same page

#### B: Profile Section

##### B.1: Social Media Icons

**Given** I am on Siobhan Powell's portfolio website\
**When** I click on the LinkedIn or GitHub icons in the profile section\
**Then** I should be redirected to the respective social media profile in a new tab

##### B.2: Download CV Button

**Given** I am on Siobhan Powell's portfolio website\
**When** I click on the "Download CV" button\
**Then** Siobhan Powell's CV should be downloaded

#### C: About Section

##### C.1: About Section Content

**Given** I am on Siobhan Powell's portfolio website\
**When** I scroll to the "About" section\
**Then** I should see all details about Siobhan Powell, including education and experience

#### D: Experience Section

##### D.1: Experience Details

**Given** I am on Siobhan Powell's portfolio website\
**When** I scroll to the "Experience" section\
**Then** I should see all listed technologies and tools under "Automation Engineering" and "QA Lead Skills" with correct proficiency levels

#### E: Projects Section

##### E.1: Project Details

**Given** I am on Siobhan Powell's portfolio website\
**When** I scroll to the "Projects" section\
**And** I click on the "GitHub" or "Live Demo" buttons for each project\
**Then** I should be redirected to the respective GitHub repository or live demo link in a new tab

#### F: Contact Section

##### F.1: Contact Information

**Given** I am on Siobhan Powell's portfolio website\
**When** I scroll to the "Contact" section\
**Then** I should see the email address and LinkedIn profile link displayed correctly and clickable

#### G: Footer Navigation

##### G.1: Footer Navigation Links

**Given** I am on Siobhan Powell's portfolio website\
**When** I scroll to the footer section\
**And** I click on each navigation link in the footer ("About", "Experience", "Projects", "Contact")\
**Then** I should be scrolled to the corresponding section on the same page

#### H: General Tests

##### H.1: Page Title and Favicon

**Given** I am on Siobhan Powell's portfolio website\
**Then** the page title should be "siobhan.zip"\
**And** the favicon should be displayed correctly in the browser tab

##### H.2: Responsiveness

**Given** I am on Siobhan Powell's portfolio website\
**When** I resize the browser window from desktop to mobile sizes\
**Then** the layout should adjust properly\
**And** the hamburger menu should appear on mobile view