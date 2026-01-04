# Bug Reporting & Feature Request Forum Setup

This repository is configured as a bug reporting and feature request forum for the private **ProofOrbit** desktop application and **ProofOrbit Website** projects.

## 📋 What's Included

### Issue Templates

Two issue templates are available when creating a new issue:

1. **🐞 Bug Report** - For reporting bugs in ProofOrbit desktop or website
   - Structured form for bug details
   - Project selection (Desktop, Website, or Both)
   - Steps to reproduce, expected vs actual behavior
   - Environment details
   - Severity classification

2. **✨ Feature Request** - For suggesting new features
   - Structured form for feature proposals
   - Project selection
   - Problem statement and proposed solution
   - Priority classification
   - Use cases and mockups

### Configuration

- **Blank issues disabled** - Users must choose a template
- **Contact links** - Links to documentation and discussions
- **Auto-labels** - Bug reports get `bug` and `triage` labels; feature requests get `enhancement` and `triage` labels

## 🏷️ Setting Up Labels

To complete the forum setup, you need to create the recommended labels in GitHub:

### Quick Setup (Recommended)

1. Go to **Settings** → **Issues** → **Labels** in this repository
2. Review the labels list in [`.github/LABELS.md`](.github/LABELS.md)
3. Create the following essential labels:

#### Essential Labels (Priority 1)
- `bug` (#d73a4a, red) - Something isn't working
- `enhancement` (#a2eeef, light blue) - New feature or request
- `triage` (#ffffff, white) - Needs initial review
- `desktop` (#1d76db, blue) - ProofOrbit desktop application
- `website` (#0075ca, dark blue) - ProofOrbit website

#### Priority Labels (Priority 2)
- `critical` (#b60205, dark red) - Critical bug
- `high-priority` (#d93f0b, orange-red) - High priority
- `medium-priority` (#fbca04, yellow) - Medium priority
- `low-priority` (#0e8a16, green) - Low priority

#### Status Labels (Priority 3)
- `in-progress` (#c5def5, pale blue) - Currently being worked on
- `blocked` (#e99695, light red) - Blocked by dependencies
- `needs-info` (#d876e3, pink) - More information needed
- `wontfix` (#ffffff, white) - Will not be fixed
- `duplicate` (#cfd3d7, gray) - Duplicate issue
- `invalid` (#e4e669, yellow-gray) - Invalid issue

See [`.github/LABELS.md`](.github/LABELS.md) for the complete list including platform-specific and quality labels.

### Alternative Setup (Using GitHub CLI)

If you have GitHub CLI (`gh`) installed and authenticated, you can create labels programmatically. See the LABELS.md file for the complete list.

## 🚀 Using the Forum

### For Users

1. Click the **Issues** tab
2. Click **New Issue**
3. Choose between **Bug Report** or **Feature Request**
4. Fill out the form completely
5. Submit the issue

### For Maintainers

1. **Triage new issues** - Remove `triage` label after initial review
2. **Apply project labels** - Add `desktop` or `website` labels
3. **Set priority** - Add priority labels based on severity/importance
4. **Update status** - Add status labels as work progresses
5. **Add platform labels** - For platform-specific bugs (Windows, macOS, Linux, browsers)
6. **Close resolved issues** - Document resolution in comments

## 📚 Additional Resources

- [GitHub Issue Templates Documentation](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
- [GitHub Labels Documentation](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)

## 🔒 Privacy Note

This repository is set up for **private** ProofOrbit projects. Ensure that:
- Repository visibility settings are configured appropriately
- Only authorized users have access to create and view issues
- Sensitive information is not included in issue descriptions
