# Intro to Open Source with OpenSauced Notes

## Sections Checklist

- [x] 1. Intro
- [x] 2. What Is Open Source?
- [x] 3. Why Open Source?
- [x] 4. Tools to be successful
- [x] 5. How to contribute to open source
- [x] 6. The Secret Sauce
- [x] 7. Conclusion
- [x] 8. Additional Resources
- [x] 9. Glossary

## 1. Intro to Open Source with OpenSauced

## 2. What Is Open Source?

- The Open Source Initiative (OSI)
  - <https://opensource.org/>

[How I coined the term 'open source'](https://opensource.com/article/18/2/coining-term-open-source-software)

### The Rise of Corporate Involvement

- Google's TensorFlow
- Facebook's React

## 3. Why Open Source?

1. Access to Knowledge
2. Access to Community
3. Access to Skills

4. Additional Benefits

In addition to the above-mentioned benefits, contributing to open source projects can also provide several other advantages, such as:

    1. **Increased job opportunities:** Many employers value open source experience and actively seek out candidates who have a proven track record of contributing to open source projects. By showcasing your open source contributions, you can increase your chances of landing your dream job or advancing your career.

    2. **Personal fulfillment:** Contributing to open source projects can be a rewarding and fulfilling experience, both personally and professionally. By sharing your skills and knowledge, you can make a tangible difference in the world and contribute to something greater than yourself.

    3. **Opportunities for recognition:** Open source projects often attract the attention of industry leaders, influencers, and media outlets. By making significant contributions to high-profile projects, you can gain recognition and establish yourself as an expert in your field.

## 4. Tools to be Successful

Essential Tools for open source collaboration:

- Git & GitHub
- CodeSee
- VS Code
- Discord

### Git & GitHub

- Git
  - branching
  - staging area
  - distributed version control

- GitHub
  - issue tracking
  - pull requests
  - forking
  - GitHub Actions

### CodeSee

CodeSee is a powerful visualization tool that helps developers understand complex codebases and navigate large projects more efficiently. By providing a visual representation of your code, CodeSee enables you to:

- Identify dependencies: CodeSee helps you understand how different parts of your codebase are connected and how changes in one area might impact other areas.
- Analyze code structure: CodeSee allows you to visualize the structure of your code, making it easier to identify patterns, anti-patterns, and areas for improvement.
- Navigate large codebases: With CodeSee, you can quickly navigate large codebases and find the parts of the code you need to work on.

To get started with CodeSee, visit the official website (<https://www.codesee.io/>) and follow the instructions to install the browser extension and integrate it with your GitHub account.

### VS Code

- built-in Git support
- extensibility
- integrated terminal
- customizable

### Discord

- connect with other developers
- stay-up-to-date
- participate in discussions
- find collaboration opportunities

## 5. How to Contribute to Open Source

### Finding projects

1. Browse GitHub via keywords, programming languages, or topics
2. Follow your interests: tools, frameworks, libraries that you use and/or interest you
3. Join open source communities: e.g., OpenSauced Discord
4. Leverage OpenSauced

#### Discover Open Source with OpenSauced

1. create account
2. explore the dashboard
3. search for projects
4. save projects to your insights
5. start contributing

### Getting Started with Contributing

1. Familiarize yourself with the project.
   1. read the `README` file
   2. read the `CONTRIBUTING` file
   3. study the project's codebase, structure, and existing issues.

2. Find an issue or create an issue
   1. look for issues labeled "good first issue" or "beginner-friendly" that are suitable for your skill level
   2. or identify a feature or improvement you'd like to work on and check if it aligns with the project's roadmap

3. Ask to be assigned the issue
   1. ask the maintainers to assign the issue to you
   2. if no directions in `CONTRIBUTING` file, comment in the issue: "Can I please be assigned this issue?"
   3. When assigned, you'll notice that the issue is now labeled with your username.

### How to Submit a Contribution

1. Fork the repository
2. Clone your fork to your local machine
3. Create a new branch
    `git checkout -b your-branch-name`
4. Make your changes
5. Commit your changes

    git add .
    git commit -m "Your commit message"

6. push your changes
7. submit a pull request
8. respond to feedback

### Let's Get Practical

1. Fork the repo
2. Clone the repo
3. Run `npm install`
4. Create a new branch
5. Run `npm run contributors:add` to add yourself to the contributors list and fill out the form based on your contributions.
6. Run `npm run contributors: generate` to generate the new contributors list.
7. Commit your changes and push them to your forked repository.
8. Once pushed, navigate to the original project's repository on GitHub and click the "New pull request" button. In the "base repository" dropdown, select the original repository, and in the "head repository" dropdown, select your forked repository. Choose your branch from the "compare" dropdown, and click "Create pull request". Fill in the required information and submit your pull request.

Congratulations! You just made an open source contribution! In the next chapter, we'll add this to an open source portfolio: a resume for open source contributions through which you can showcase your work and attract potential employers and friends using OpenSauced. For now, let's wrap up with some notes on onboarding.

### Merge Conflicts

Step-by-Step Guide

1. Open VS Code: Launch Visual Studio Code and open the repository where the merge conflict exists.
2. Check for Conflicts: If you've just performed a pull or merge operation and a conflict occurs, VS Code will automatically detect it. You will see a notification in the source control tab or sidebar.
3. View Conflicted Files: Click on the conflicted file in the source control tab. VS Code will display a "Merge Conflict" section in the file.
4. Resolve Conflicts: Inside the "Merge Conflict" section, you'll see the conflicting changes separated by the conflict markers (<<<<<<<, =======, >>>>>>). From there, decide which changes to keep or combine.
5. Save the file: After resolving the conflicts, save the file.
6. Stage the Resolved File: In the Source Control tab, you should see options to stage the resolved file. Click on the "Mark as Resolved" or similar button.
7. Commit the Changes: Once all conflicts are resolved, commit your changes using VS Code's built-in source control features.
8. Push Your Changes: After committing, push the changes to the remote repository to complete the merge process.
9. Verify the Merge: Verify that the merge conflict has been successfully resolved by checking the remote repository or using Git tools.

### Onboarding in a New Project

1. Read the documentation
2. Join the community
3. Start small
4. Ask for help
5. Be patient and persistent

### What Happens Next?

1. Your contribution is accepted
2. Your contribution requires changes
3. Your contribution is rejected

## 6. The Secret Sauce

- how to focus on open issues
- gain traction in contributions
- develop your open source resume with OpenSauced

### Open Issues - More than PRs that Fix Typos

Tackle open issues to help the project move forward and give yourself a deeper understanding of the codebase and demonstrate your problem-solving abilities.

Tips for finding and addressing open issues:

1. Browse the issue tracker
2. Look for beginner-friendly issues
3. Understand the issue
4. Communicate your intentions
5. Test your changes

Focus on open issues rather than just fixing typos, so you'll make a more significant impact on the projects you contribute to and demonstrate your commitment to the open source community.

### Get Traction in Contributions

1. Become a regular contributor
2. Take on challenging tasks
3. Collaborate with others
4. Share your expertise
   1. write blog posts
   2. create tutorials
   3. give presentations
5. Mentor new contributors

### Build Your Open Source Resume

Use OpenSauced to track your open source contributions and develope your open source resume

1. Sign up for an OpenSauced account
2. Visit your public profile page
3. Build your open source resume
   1. add highlights to Pull Requests and Issues that you've contributed to
   2. also add description and links to your open source resume

Showcase the guestbook contribution

- locate "Highlights" section with a text input
- click on this section
  - add a title
  - some thoughts
  - a link to your PR
- displayed on your public profile page

#### Effectively Highlight Your Contribution

Important information to include when you're highlighting your contributions:

- New material you've created,
- Project details (tools, libraries, size, and complexity),
- The type of your contributions: bug fix, feature, performance, documentation, - etc.,
- The details of your contribution including improvements and impacts made on the - project and on the community,
- Collaboration and teamwork details.

#### Formatting Your Highlight

Recommended Format:

- **Description**: When highlighting your contribution, we recommend mentioning the impact that it had on the overall project. This would be helpful in highlighting your qualifications for job positions, especially if you have employment gaps. Consider using the following model to help you craft this highlight into a story:
  - Success verb + noun + metric + outcome.
  - Example: While I was reviewing some pull requests for this year's GirlScript Summer of Code, I noticed that most of them would not merge in spite of me and the owner giving approvals. So, I created a GitHub Action where pull requests automatically merge once they have passed the deployment steps(successive verb + noun), which increased productivity rates by 80%(metric + outcome).
- Add a repo: Provide the complete name of the repository to which you are making contributions.
- URL: Paste the URL to your pull request, issue or your blog post.

Share it!: Once you've built up a portfolio of open source contributions, you can share your OpenSauced resume with others by clicking the share button in the header of your profile page. This can be especially helpful when applying for jobs, networking with other developers, or promoting your work in the open source community.

By leveraging OpenSauced to track your open source contributions and develop your resume, you'll be better equipped to showcase your skills, experience, and impact in the open source community.

In conclusion, getting started with open source contributions and making a lasting impact on the projects you work on requires a combination of technical skills, collaboration, and persistence. By focusing on open issues, gaining traction in your contributions, and leveraging tools like OpenSauced, you'll be well on your way to a successful and fulfilling open source journey.

## 7. Types of Contributions

### Non-Coding Types of Contributions

- documentation
- graphic design
- blog writing

### Coding Type of Contributions

- write new code
- bug fixes
- code refactoring
- API design and maintenance
- feature development
- performance optimization
- testing and quality assurance

## 8. Additional Resources

[Introduction to contributing](https://docs.opensauced.pizza/contributing/introduction-to-contributing/)

## 9. Conclusion

### What's Next

1. Identify your interests and goals
2. Find projects to contribute to
3. Start contributing
4. Connect with the open source community
5. Attend events and conferences
6. Share your experiences
7. Continue learning

## 10. Glossary

End
