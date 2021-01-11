# Pull Request Template

## Description

Please include a summary of the change and which issue (state the issue number) is fixed. Also include relevant motivation & context. If a new dependency is required for this change, include it in the description as well. State the reasons why and how the new dependency helps.

Fixes #(Insert Issue Here Without Brackets)

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

**Note**: Insert an "x" between the "[ ]" where applicable.

## How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Also, list any relevant details for your test configuration.

**Note**: If you're fixing an issue ensure the existing tests passes. If you're adding a new feature, write tests for those features & ensure all the test pass including the existing ones.

**Test Configuration(s)**:

**Note**: `pytest` has very sensible default configurations setup out-of-the-box. But in case, you've configured your session of `pytest` to run differently, do list those configurations below. You can find documentations of the configurations [here](https://docs.pytest.org/en/stable/reference.html#configuration-options).

Here's an example configuration (_replace them with yours_):

- `addopts = --maxfail=2 -rf`
- `cache_dir = path/to/the/cache/directory`

Replace the example section with your configurations. Before that, ensure your configurations plays well with Black & the `pytest`'s `pyproject.toml` [specification](https://docs.pytest.org/en/stable/customize.html#pyproject-toml).

## Checklist

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my code
- [ ] I have commented on my code particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation if it was necessary
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules
- [ ] I have checked my code and corrected any misspellings
