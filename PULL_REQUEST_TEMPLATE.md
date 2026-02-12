# Overview
<!-- What is the story behind this change -->

# Objectives
<!-- What are you aiming to achieve because of this change -->

# Why
<!-- What is the change for the customer - why is it important -->

# Risks
<!-- What could go wrong - what components and/or processes can see this change. Does this change have any performance impacts? How has it been assessed? -->

# Pipeline Changes
<!-- Describe how this change impacts the build and deployment pipelines -->

# Testing Environment
<!-- Specify where this change was tested, e.g., locally, specific lab, team lab -->

Thank you for your contribution to the MaxContact repo. 
Before submitting this PR, please make sure:

- [ ] There is a clear title and description
- [ ] Your code builds clean without any errors
- [ ] Coding standards have been followed and changes are consistent with the rest of the product
- [ ] You have added sufficient unit tests that cover both edge cases and typical scenarios and they execute successfully
- [ ] OWASP security has been reviewed, including new third-party libraries, input validation, authentication on new ingress points, and data encryption if applicable
- [ ] Any potential risks are highlighted including elsewhere this code could impact
- [ ] Testing notes have been updated on the linked ticket
- [ ] Appropriate logging has been added, including error handling and debug information
- [ ] Code comments are clear and explain any complex logic or decisions
- [ ] SQL code executes successfully, including "IF NOT EXISTS" and "ON CONFLICT DO NOTHING" to ensure idempotency and avoid duplicate conflicts
- [ ] Additional testing has been done locally by another team member (indicate who and what was tested)
- [ ] Any changes have been updated to schema as required
