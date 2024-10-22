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
- [ ] After automatic checks are posted, use the editor template to guide initial checks and record your response to the submission. You can also streamline your editor checks by using the pkgreviewr package created by associate editor Anna Krystalli. Please strive to finish the checks and start looking for reviewers within 5 working days.
- [ ] Check that template has been properly filled out.
- [ ] Check against policies for fit and overlap. Initiate discussion via Slack #software-review channel if needed for edge cases that haven’t been caught by previous checks by the EiC. If reject, see this section about how to respond.
- [ ] Check that mandatory parts of template are complete. If not, direct authors toward appropriate instructions.
- [ ] For packages needing continuous integration on multiple platforms (cf criteria in this section of the CI chapter) make sure the package gets tested on multiple platforms (having the package built on several operating systems via GitHub Actions for instance).
- [ ] Wherever possible when asking for changes, direct authors to automatic tools such as usethis and styler, and to online resources (sections of this guide, sections of the R packages book) to make your feedback easier to use. Example of editor’s checks.
- [ ] Ideally, the remarks you make should be tackled before reviewers start reviewing.
- [ ] If initial checks show major gaps, request changes before assigning reviewers. If the author mentions changes might take time, apply the holding label via typing @ropensci-review-bot put on hold. You’ll get a reminder every 90 days (in the issue) to check in with the package author(s).
- [ ] If the package raises a new issue for rOpenSci policy, start a conversation in Slack or open a discussion on the rOpenSci forum to discuss it with other editors (example of policy discussion).
