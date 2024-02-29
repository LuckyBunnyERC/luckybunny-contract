# Contributing to Lucky Protocol

🎉 First off, thanks for taking the time to contribute! 🎉

The following is a set of guidelines for contributing to Lucky Protocol, which is hosted on GitHub and mainly written in Solidity. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Code of Conduct

This project and everyone participating in it is governed by the [Lucky Protocol Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for Lucky Protocol. Following these guidelines helps maintainers and the community understand your report 📝, reproduce the behavior 💻, and find related reports 🔎.

**Before submitting a bug report:**

- Check the [issues](https://github.com/LuckyBunnyERC/luckybunny-contract/issues) for a list of proposed features, ongoing issues, and submitted bug reports.
- Perform a cursory search to see if the problem has already been reported. If it has, add a comment to the existing issue instead of opening a new one.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Lucky Protocol, including completely new features and minor improvements to existing functionality.

- Fill in the [feature request template](feature_request.md), including the steps that you imagine you would take if the feature you're requesting existed.

### Pull Requests

The process described here has several goals:

- Maintain the project's quality
- Fix problems that are important to users
- Engage the community in working toward the best possible version of Lucky Protocol

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing

#### Styleguides

##### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

##### Solidity Styleguide

- Follow the [Solidity Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html)
- Ensure code is well-documented and follows the NatSpec format
- Write tests for all new code
- Ensure that contracts are well-tested and securely audited

##### Documentation Styleguide

- Use Markdown for documentation
- Document all functions and modules clearly
- Example: 
  ```solidity
  // @notice Calculates and returns the square of the given number
  // @param num The number to be squared
  // @return The square of the input number
  function square(uint num) public pure returns (uint) {
      return num * num;
  }
