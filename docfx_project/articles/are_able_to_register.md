## Scenario: Visitors are able to register

- **Given** the visitor is on the home ScreenGiven the  visitor is NOT logged in
- **When** the visitor clicks the register button
- **Then** the login screen is loaded
- **When** the visitor types his email
- **When** the visitor types his password
- **When** the visitor types his password again
- **When** the visitor clicks the register button
- **Then** the confirmation text is displayed

