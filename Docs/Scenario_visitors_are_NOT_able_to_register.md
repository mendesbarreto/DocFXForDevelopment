## Scenario: Visitors are NOT able to register

**Given** the visitor is on the home screen
**Given** the visitor is NOT logged in
**When** the visitor clicks the register button
**Then** the login screen is loaded
**When** the visitor types the email john.doe@example.com
**When** the visitor types the password secret
**When** the visitor types the validation password secret
**When** the visitor clicks the register button
**Then** the text Password must be at least 8 characters long is displayed