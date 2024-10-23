# review-rredlist

Guest editing for rOpenSci's software review of `rredlist`

- https://github.com/ropensci/software-review/issues/663

Resources:

- https://devguide.ropensci.org/softwarereview_editor.html

## TODO

- [ ] see fixes list for devguide


From submission: 

- [X] check differences in package coverage


Upon submission:

- Submission will automatically generate package check output from ropensci-review-bot which should be examined for any outstanding issues (most exceptions will need to be justified by the author in the particular context of their package.). If you want to re-run checks after any package change post a comment @ropensci-review-bot check package.
- [X] After automatic checks are posted, use the editor template to guide initial checks and record your response to the submission. You can also streamline your editor checks by using the pkgreviewr package created by associate editor Anna Krystalli. Please strive to finish the checks and start looking for reviewers within 5 working days.
- [X] Check that template has been properly filled out.
- [X] Check against policies for fit and overlap. Initiate discussion via Slack #software-review channel if needed for edge cases that haven’t been caught by previous checks by the EiC. If reject, see this section about how to respond.
- [X] Check that mandatory parts of template are complete. If not, direct authors toward appropriate instructions.
- [X] For packages needing continuous integration on multiple platforms (cf criteria in this section of the CI chapter) make sure the package gets tested on multiple platforms (having the package built on several operating systems via GitHub Actions for instance).
- [X] Wherever possible when asking for changes, direct authors to automatic tools such as usethis and styler, and to online resources (sections of this guide, sections of the R packages book) to make your feedback easier to use. Example of editor’s checks.
- [X] Ideally, the remarks you make should be tackled before reviewers start reviewing.
- [X] If initial checks show major gaps, request changes before assigning reviewers. If the author mentions changes might take time, apply the holding label via typing @ropensci-review-bot put on hold. You’ll get a reminder every 90 days (in the issue) to check in with the package author(s).
- [X] If the package raises a new issue for rOpenSci policy, start a conversation in Slack or open a discussion on the rOpenSci forum to discuss it with other editors (example of policy discussion).

Look for and assign two reviewers:

- [ ] Comment with @ropensci-review-bot seeking reviewers.
- [ ] Review criteria for choosing a reviewer:
  - Has not reviewed a package for us within the last 6 months.
  - Some package development experience.
  - Some domain experience in the field of the package or data source
  - No conflicts of interest.
  - Try to balance your sense of the potential reviewer’s experience against the complexity of the package.
  - Diversity - with two reviewers both shouldn’t be cis white males.
  - Some evidence that they are interested in openness or R community activities, although cold emailing is fine.
  - Each submission should be reviewed by two package reviewers. Although it is fine for one of them to have less package development experience and more domain knowledge, the review should not be split in two. Both reviewers need to review the package comprehensively, though from their particular perspective. In general, at least one reviewer should have prior reviewing experience, and of course inviting one new reviewer expands our pool of reviewers.
- [ ] Use the email template if needed for inviting reviewers
  - [ ] When inviting reviewers, include something like “if I don’t hear from you in a week, I’ll assume you are unable to review,” so as to give a clear deadline when you’ll move on to looking for someone else.
- [ ] Assign reviewers with @ropensci-review-bot assign @username as reviewer. add can also be used instead of assign, and to reviewers (plural) instead of as reviewer (single). The following is thus also valid: @ropensci-review-bot add @username to reviewers. One command should be issued for each reviewer. If needed later, remove reviewers with @ropensci-review-bot remove @username from reviewers.
- [ ] If you want to change the due date for a review use @ropensci-review-bot set due date for @username to YYYY-MM-DD.


