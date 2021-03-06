Make sure you have checked _all_ steps below.

### Jira

- [ ] My PR addresses the following [Parquet Jira](https://issues.apache.org/jira/browse/PARQUET/) issues and references them in the PR title. For example, "PARQUET-1234: My Parquet PR"
  - https://issues.apache.org/jira/browse/PARQUET-XXX
  - In case you are adding a dependency, check if the license complies with the [ASF 3rd Party License Policy](https://www.apache.org/legal/resolved.html#category-x).

### Commits

- [ ] My commits all reference Jira issues in their subject lines. In addition, my commits follow the guidelines from "[How to write a good git commit message](http://chris.beams.io/posts/git-commit/)":
  1. Subject is separated from body by a blank line
  1. Subject is limited to 50 characters (not including Jira issue reference)
  1. Subject does not end with a period
  1. Subject uses the imperative mood ("add", not "adding")
  1. Body wraps at 72 characters
  1. Body explains "what" and "why", not "how"

### Documentation

- [ ] In case of new functionality, my PR adds documentation that describes how to use it.
  - All the public functions and the classes in the PR contain Javadoc that explain what it does
