# Release flow
_for projects multiple feature branches and when only part of them are going on production so far_

1. PM sets deploy date with the client.
2. Developer makes to branch next
  * rebase
  * merge
  for all the feature branches that will be deployed.
3. Developer deploys to staging from branch next.
4. Developer and/or QA test the release on staging.
5. On told date (from point 1) developer merges branch next to master and deploys it to production.
