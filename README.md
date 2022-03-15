# Dokobit backend assignment

## Description
Create a single REST API endpoint that allows users to upload multiple files with a single request, archive them and return a single zip file. Store
upload statistics: IP address and usage count per day in the database.

Save your time and do not implement a fully working SaaS solution. We want to evaluate your class design skills and PHP knowledge. We will
look at:
- Class structure and given recommendations on future improvements.
- Test quality.
- Ability to use existing components and packages.

## Requirements
- Use PHP as a server-side programming language.
- Use a modern PHP framework to complete this task. Symfony would work just fine.
- There is no need for a GUI. All interactions should be available through an API.
- Max file upload size is 1 MB.
- Code has to be covered by tests. We use phpspec and PHPUnit, but you can use any other testing framework sufficient for this task.
- Provide a solution using GitHub. It would be great to find the whole commit history, not only a single entry.
- Provide a README file with your thoughts on how your code would adapt to the following changes and what design choices have you
- made to meet these changes more easily:
  1. If we add multiple archiving methods (7z, for example);
  2. Face a significant increase in request count;
  3. Allow 1GB max file size;
